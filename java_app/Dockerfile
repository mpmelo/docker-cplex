FROM d_cplex_cplex

COPY src/ /app/

WORKDIR /app

ENTRYPOINT ["java","-Djava.library.path=/opt/ibm/ILOG/CPLEX_Studio201/cplex/bin/x86-64_linux","-cp",".:/opt/ibm/ILOG/CPLEX_Studio201/cplex/lib/cplex.jar","HelloCplex"]
