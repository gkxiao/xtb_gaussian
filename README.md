<h2>Example 1. Optimization</h2>
<p>Prepare a opt job file,xtb_opt.com</p>
<pre lang="shell">
%chk=CONF_89_xtb.chk
#P OPT external="./xtb_external.py"
 
Structure: CONF_89 Calculation: Opt at xTB-GNF2 level
 
0 1
C -2.8524 0.3435 1.4345
C -2.6391 0.4571 -0.0494
C -3.2889 1.6673 -0.6703
C -1.9378 -0.4063 -0.81
C -1.2167 -1.6555 -0.3826
C 0.2859 -1.6077 -0.6948
C 1.0895 -0.516 0.051
C 2.527 -0.4782 -0.5183
C 3.419 0.6221 0.0524
O 2.8233 1.901 -0.1057
C 1.0942 -0.7594 1.5629
H -2.4247 -0.5601 1.8719
H -3.9242 0.3334 1.6597
H -2.4018 1.2014 1.9447
H -3.1115 1.7286 -1.7492
H -4.3721 1.6385 -0.5131
H -2.895 2.5829 -0.2169
H -1.8681 -0.2053 -1.8795
H -1.3742 -1.897 0.6703
H -1.6538 -2.4922 -0.9426
H 0.4088 -1.4666 -1.7772
H 0.7165 -2.5914 -0.4657
H 0.621 0.4571 -0.1385
H 3.0166 -1.4477 -0.364
H 2.4582 -0.325 -1.6033
H 4.3841 0.6288 -0.465
H 3.621 0.4644 1.1154
H 2.6113 2.0125 -1.048
H 1.6225 0.0387 2.0931
H 1.5793 -1.71 1.8085
H 0.0799 -0.7824 1.9697

! Here is a blank line
</pre>
<p>Perform optimization:</p>
<pre lang="shell">
g16 xtb_opt.com
</pre>
