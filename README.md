# MolNFT-HLA
HLA db predicted with Meta AI ESMFold 2 by M for GenesisL1

This repository contains information about MolNFT HLA - standard ERC-721 tokens on GenesisL1 blockchain containing HLA db sequential information and HLA protein structures predicted with Meta AI ESMFold2 by M for GenesisL1 blockchain. 

<h3>Experiment:</h3>

Predict all HLA db protein sequences with Meta AI ESMFold 2 and Single GPU Nvidia RTX 3090. 
Lamdalabs setup:
https://lambdalabs.com/blog/install-tensorflow-and-pytorch-on-rtx-30-series

<h3>Files:</h3>
hla_db_prediction_pLDDT_pTM_time.txt - each prediction Time, pTM and plDDT.

<h3>References:</h3>

<li>The IPD-IMGT/HLA Database (https://www.ebi.ac.uk/ipd/imgt/hla/) </li>
<pre>


    Robinson, J., Barker, D.J., Georgiou, X., Cooper, M.A. and Marsh, S.G.
    The IPD-IMGT/HLA Database.
    Nucleic Acids Res (2020), 48 D948-55.
    Maccari, G., Robinson, J., Hammond, J.A. and Marsh, S.G.E.
    The IPD Project: a centralised resource for the study of polymorphism in genes of the immune system
    Immunogenetics. Immunogenetics (2019), In press.
    Bruijnesteijn, J., de Groot, N., Otting, N., Maccari, G., Guethlein, L.A., Robinson, J., Marsh, S.G.E., Walter, L., O’Connor, D.H., Hammond, J.A. et al.
    Nomenclature report for killer cell immunoglobulin-like receptors (KIR) in macaque species – New genes/alleles, renaming hybrid entities and IPD-NHKIR updates.
    Immunogenetics, In press. (2019)
    Maccari, G., Robinson, J., Bontrop, R.E., Otting, N., de Groot, N.G., Ho, C.S., Ballingall, K.T., Marsh, S.G.E. and Hammond, J.A.
    IPD-MHC: nomenclature requirements for the non-human major histocompatibility complex in the next-generation sequencing era.
    Immunogenetics (2018), 70 619-623
    Maccari, G., Robinson, J., Ballingall, K., Guethlein, L.A., Grimholt, U., Kaufman, J., Ho, C.S., de Groot, N.G., Flicek, P., Bontrop, R.E. et al.
    IPD-MHC 2.0: an improved inter-species database for the study of the major histocompatibility complex.
    Nucleic Acids Res (2017), 45 D860-D864.
    Robinson, J., Soormally, A.R., Hayhurst, J.D. and Marsh, S.G.
    The IPD-IMGT/HLA Database - New developments in reporting HLA variation.
    Hum Immunol (2016), 77 233-237.
    Robinson, J., Halliwell, J.A., Hayhurst, J.D., Flicek, P., Parham, P. and Marsh, S.G.E.
    The IPD and IMGT/HLA database: allele variant databases.
    Nucleic Acids Res (2015), 43 D423-431.
    Robinson, J., Halliwell, J.A., McWilliam, H., Lopez, R., Parham, P. and Marsh, S.G.E.
    The IMGT/HLA Database.
    Nucleic Acids Res (2013), 41 D1222-1227.
    Robinson, J., Halliwell, J.A., McWilliam, H., Lopez, R. and Marsh, S.G.E.
    IPD -- the Immuno-Polymorphism Database.
    Nucleic Acids Res (2013), 41 D1234-1240.
    Robinson, J., Mistry, K., McWilliam, H., Lopez, R., Parham, P. and Marsh, S.G.E.
    The IMGT/HLA database.
    Nucleic Acids Res (2011), 39 D1171-1176.
    Robinson, J., Mistry, K., McWilliam, H., Lopez, R. and Marsh, S.G.E.
    IPD -- the Immuno Polymorphism Database.
    Nucleic Acids Res (2010), 38 D863-869.
    Robinson, J., Waller, M.J., Fail, S.C., McWilliam, H., Lopez, R., Parham, P. and Marsh, S.G.E.
    The IMGT/HLA database.
    Nucleic Acids Res (2009), 37 D1013-1017.
    Robinson, J., Waller, M.J., Fail, S.C. and Marsh, S.G.E.
    The IMGT/HLA and IPD databases.
    Hum Mutat (2006), 27 1192-1199.
    Robinson, J., Waller, M.J., Stoehr, P. and Marsh, S.G.E.
    IPD -- the Immuno Polymorphism Database.
    Nucleic Acids Res (2005), 33 D523-526.
    Robinson, J., Waller, M.J., Parham, P., de Groot, N., Bontrop, R., Kennedy, L.J., Stoehr, P. and Marsh, S.G.E.
    IMGT/HLA and IMGT/MHC: sequence databases for the study of the major histocompatibility complex.
    Nucleic Acids Res (2003), 31 311-314.
    Robinson, J., Waller, M.J., Parham, P., Bodmer, J.G. and Marsh, S.G.E.
    IMGT/HLA Database -- a sequence database for the human major histocompatibility complex.
    Nucleic Acids Res (2001), 29 210-213.
    Ruiz, M., Giudicelli, V., Ginestoux, C., Stoehr, P., Robinson, J., Bodmer, J., Marsh, S.G.E., Bontrop, R., Lemaitre, M., Lefranc, G. et al.
    IMGT, the international ImMunoGeneTics database.
    Nucleic Acids Res (2000), 28 219-221.
    Robinson, J. and Marsh, S.G.E.
    The IMGT/HLA sequence database.
    Rev Immunogenet (2000), 2 518-531.
    Robinson, J., Malik, A., Parham, P., Bodmer, J.G. and Marsh, S.G.E.
    IMGT/HLA database--a sequence database for the human major histocompatibility complex.
    Tissue antigens (2000), 55 280-287.


</pre>
<li>Meta AI ESMFold2 (https://github.com/facebookresearch/esm) </li>
<pre>Evolutionary-scale prediction of atomic level protein structure with a language model
Zeming Lin, Halil Akin, Roshan Rao, Brian Hie, Zhongkai Zhu, Wenting Lu, Nikita Smetanin, Robert Verkuil, Ori Kabeli, Yaniv Shmueli, Allan dos Santos Costa, Maryam Fazel-Zarandi, Tom Sercu, Salvatore Candido, Alexander Rives
bioRxiv 2022.07.20.500902; doi: https://doi.org/10.1101/2022.07.20.500902 </pre>
<li>MolNFT: ERC-721 NFT of sequences and molecular structures (MolNFT.org) on GenesisL1 blockchain.</li>
<li>GenesisL1: public decentralized Layer 1 EVM blockchain based on Cosmos SDK (genesisL1.com)</li>
