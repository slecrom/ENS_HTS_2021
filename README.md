# Functional genomic data analysis: transcriptomics - Practical

1. Direct access to practical content
   - [Microarrays](./Microarrays/README.md)
   - [RNAseq](./RNAseq/TD_RNAseq.md)
2. [Connect to the IFB server](#connect-to-the-ifb-server)
3. [Connect to the IFB Rstudio server](#connect-to-the-ifb-rstudio-server)

## Connect to the IFB server 

For this part of the practical, you will work remotely on the [IFB-core cluster](https://www.france-bioinformatique.fr/le-cluster-ifb-core/) located in **Orsay (IDRIS)**. Because it it a shared infrastructure you will have to pay attention to the command you use to start a job. **They all must start with *srun***.  
You can refer to [IFB Core Cluster Documentation](https://ifb-elixirfr.gitlab.io/cluster/doc/) for more detail about logging, data management, job submission. 

#### Sign in on the server
  * On Windows using [MobaXterm](https://mobaxterm.mobatek.net/)
  
> 1. In **Session** > **SSH**  
> Remote Host : core.cluster.france-bioinformatique.fr  
> Specify username : ticked and filled in **your login**
> Advanced SSH settings : tick X11-Forwarding  
> 2. Enter your password
> 3. You should be logged on the IFB Core cluster 

<p align="center">

<img src="./TD_RNAseq/images/MobaXtrem.png" width="100%">

</p>

  * On MacOS and Linux using a terminal window
```bash
ssh <login>@core.cluster.france-bioinformatique.fr
```

## Connect to the IFB Rstudio server

In a web browser, connect to https://rstudio.cluster.france-bioinformatique.fr/auth-sign-in and log in using your user name and password (same as for ssh connection)

<p align="center">

<img src="./TD_RNAseq/images/Rstudio.png" width="30%">

</p>

You will reached the familiar Rstudio environment:

<p align="center">

<img src="./TD_RNAseq/images/RstudioScreen.png" width="50%">

</p>
