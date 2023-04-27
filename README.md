# Branch-Predictor-for-SAT-Solver

Team VVK
Team Members:  
               K.Lokesh           210050081
               V.Mahanth Naidu    210050161
               V.Raja Gopal       210050160

Binary build Command:
./build_champsim.sh [branch_pred] [l1i_pref] [l1d_pref] [l2c_pref] [llc_pref] [llc_repl] [num_core]

Run Command for trace:
./run_champsim.sh [BINARY] [N_WARM] [N_SIM] [TRACE] [OPTION]

For Graph generation file:
python3 print_graph.py [TRACE] [N_WARM] [N_SIM]

Results from the traces are found in "graph_results" folder

Traces are found in dpc3_traces folder within ChampSim-master directory

Files were added in Champsim-master/branch directory:
 loop_pred.h ltage.bpred tage.bpred tage.h
