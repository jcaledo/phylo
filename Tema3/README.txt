
## —————— pam1
pam1: matriz Dayhoff (PAM-1). p_ij es la probabilidad de que j
pase a i tras una unidad de tiempo PAM (1 % de cambio). Los 
valores hay que dividirlos por 10000 para que sean probabilidades.
La matriz dividida por 10000 y transpuesta se puede considerar la 
matriz de probabilidades de transición de un modelo de CMTC:
p_ij(t): probabilidad de que el proceso pase del estado i al estado j
tras un tiempo t.