This is a modified version of gpb: a compiler for Google protocol buffer definitions files for Erlang.

This is a project extracted from the commit number 73704d1e13246405a56f17fc7eaf7fa9ca27e194, done the 21st Oct 2016

The original tool is publicly available at: https://github.com/tomas-abrahamsson/gpb

We performed an adaptation of some of its modules in order to use some powerful parts of the tool in our work. 
%The modified modules and functions are the following:

%cuter_symbolic.erl:
%- generate_new_input/2
%
%cuter_pp.erl:
%- pp_nl/2
%- pp_solving_failure/2
%- pp_execution_status_minimal/1
%
%cuter.erl:
%- start/2
