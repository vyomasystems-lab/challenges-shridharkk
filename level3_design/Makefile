# See LICENSE.vyoma for details

TOPLEVEL_LANG ?= verilog

PWD= (shell pwd)

VERILOG_SOURCES = $(PWD)/               # provide your design path

TOPLEVEL :=           # design file in verilog
MODULE   :=     # test file in verilog

include $(shell cocotb-config --makefiles)/Makefile.sim

clean_all: clean
	rm -rf *.xml sim_build __pycache__ 
