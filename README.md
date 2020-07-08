# cpu_stress_test
A simple linux CPU stress test that hammers the CPU with the number of available threads in the system or set number of threads

# To compile using g++
  g++ -fopenmp cpu_stress.cpp -o cpu_stress

# to run
      ./cpu_stress # this will detect the number of threads availalble in the system and runs the CPY stress test until it finishes.
  
      ./cpu_stress 7  #this will launch 7 threads in the system.
 
the more threads you launch the faster the program will finish.
