### Run Example
   
#### Install Open5gs
`./cnf-testsuite cnf_setup cnf-config=./sample-open5gs/cnf-testsuite.yml`
     
#### Install RAN & UE
`./cnf-testsuite cnf_setup cnf-config=./sample-ueransim/cnf-testsuite.yml`
      
#### Run CNF Testsuite 
`./cnf-testsuite cert ~cert_resilience ~cni_compatible`

