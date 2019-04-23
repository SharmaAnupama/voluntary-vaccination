Data for Figs 2-4 of the manuscript are accessible in the form of .mat
files (which can be opened in MATLAB) available in the following folders.

[Note: Data for the empirical social newtorks used in Figures 2(a-b) and 3(d)
are openly accessible as part of the published article:
Banerjee, A., Chandrasekhar, A. G., Duflo, E. and Jackson, M. O. (2013). 
The diffusion of microfinance. Science, 341(6144), 1236498, DOI: 10.1126/science.1236498
and can be directly downloaded from
https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/21538]

---------------------------------------------------------------------------
Folder Figure_2 contains

[1] data for Fig 2(a) and Fig 2(c) left panel
("TimeSeries_Vill55_alpha0.mat")

This file contains the matrix "S_rec" of size 692x6, which corresponds
to time series data for single simulation on the village network 55
for the case alpha = 0. The 6 columns correspond to: (1) time t (2)
number of susceptible agents at time t (3) number of infected agents
at time t (4) number of recovered agents at time t (5) number of
vaccinated agents at time t (6) cumulative number of infected agents
at time t.

[2] data for Fig 2(b) and Fig 2(c) right panel
("TimeSeries_Vill55_alpha1.mat")

This file contains the matrix "S_rec" of size 924x6, which corresponds
to time series data for single simulation on the village network 55
for the case alpha = 0. The 6 columns correspond to: (1) time t (2)
number of susceptible agents at time t (3) number of infected agents
at time t (4) number of recovered agents at time t (5) number of
vaccinated agents at time t (6) cumulative number of infected agents
at time t.

[3] data for Fig 2(d) and Fig 2(e) (Folder "vill55_network")

This folder contains files for simulations on the village network 55
for the cases alpha = 0 and alpha = 1. The file names are
"vill55_qX_alphaY.mat" where X is the value of \beta and Y is the value of
alpha (0 or 1). Each .mat file contains a matrix "datavn" of size
2x1000. This contains data for inf_\infty and vac_\infty for one value
of \beta, for 1000 simulation runs.


---------------------------------------------------------------------------
Folder Figure_3 contains

[1] data for Fig 3(a) left panel ("TimeSeries_ER_alpha0.mat")

This file contains the matrix "S_rec" of size 885x6, which corresponds
to time series data for single simulation on an ER network of size
1024 for the case alpha = 0. The 6 columns correspond to: (1) time t
(2) number of susceptible agents at time t (3) number of infected
agents at time t (4) number of recovered agents at time t (5) number
of vaccinated agents at time t (6) cumulative number of infected agents
at time t.

[2] data for Fig 3(a) right panel ("TimeSeries_ER_alpha1.mat")

This file contains the matrix "S_rec" of size 1103x6, which
corresponds to time series data for single simulation on an ER network
of size 1024 for the case alpha = 1. The 6 columns correspond to: (1)
time t (2) number of susceptible agents at time t (3) number of
infected agents at time t (4) number of recovered agents at time t (5)
number of vaccinated agents at time t (6) cumulative number of infected
agents at
time t.


[3] data for Fig 3(b) and Fig 3(c) (folder "ER_network")

This folder contains files for simulations on ER networks of size 1024
for the case of local information (alpha = 0, "loc_*.mat") and global
information (alpha = 1, "glo_*.mat"). The file names are "X_glsp_qY.mat",
where X is "loc or "glo" and Y is the value of \beta. Each .mat file
contains a matrix "dataq" of size 2x1000. This contains data for
inf_\infty and vac_\infty for one value of \beta, for 1000 simulation
runs.

[4] data for Fig 3(d) (folder "Kavg_ERN_KVN")

This folder contains files for simulations on ER networks of size 1024
as well as on empirical village networks.

For the case of ER networks, the file names are
"glsp_qX_kY_alphaZ.mat", where X is the value of \beta, Y is the average
degree of the network used and Z is the value of alpha (0 or 1). Each
.mat file contains a matrix "dataq" of size 2x1000. This contains data
for inf_\infty and vac_\infty for one value of \beta, for 1000
simulation runs.

For the case of village networks, the file names are
"villX_qY_alphaZ.mat", where X is the village id, Y is the value of \beta
and Z is the value of alpha (0 or 1). Each .mat file contains a matrix
"datavn" of size 2x1000. This contains data for inf_\infty and
vac_\infty for one value of \beta, for 1000 simulation runs.


---------------------------------------------------------------------------
Folder Figure_4 contains

[1] data for Fig 4(a) (folder "ER_All_system_sizes")

This folder contains simulations on ER network for a range of system
sizes (multiples of 1024), for the case of local and global
information. The file names are "Xn_alphaY_qZ.mat", where X is the
multiple of 1024 that specifies the system size (e.g. X="02"
corresponds to a network of size 2*1024) and Y is the value of alpha
(0 or 1) and Z is the value of \beta. Each .mat file contains a matrix
"dataq" of size 2x1000. This contains data for inf_\infty and
vac_\infty for one value of \beta, for 1000 simulation runs.

[2] data for Fig 4(b) and Fig 4(c) (folder "ER_16N")

This folder contains simulations on ER network for a fixed system size
(16*1024 agents) and over a range of values of alpha. The file names
are "16n_alphaX_qY.mat", where X is the value of alpha (0 or 1) and Y
is the value of \beta. Each .mat file contains a matrix "dataq" of size
2x1000. This contains data for inf_\infty and vac_\infty for one value
of \beta, for 1000 simulation runs. An additional 1000 simulation runs are
provided in the files with names "16n2_alphaX_qY.mat", where X is the 
value of alpha (0 or 1) and Y is the value of \beta.


---------------------------------------------------------------------------
