TOP=../..
OFSRC=@openflowsrc@

CFLAGS+=-Wall -I$(OFSRC)/include -I$(TOP) -Wshadow
LDFLAGS+=-L$(TOP) -lm -L$(OFSRC)/lib/

LDADD=-ldl -lpcap -loflops_test -lopenflow

lib_LTLIBRARIES=libopenflow_aggr_flow_stats.la

libopenflow_aggr_flow_stats_la_SOURCES= aggr_flow_stats.c
