foreach( fname coupling_eigen_odeint rlc_eigen_odeint
               coupling_odeint rlc_odeint coupling_prima_eigen_odeint coupling_sprim_eigen_odeint )
  add_executable( ${fname} ${fname}.cpp )
  target_link_libraries( ${fname} Boost::boost )
endforeach()

