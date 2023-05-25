# Yale Wet Lab Protocols

This is a repository for `YSM Gunel Lab - Wet Lab Protocols`. 

## Prepared by:

**Name:** [Batur Gültekin](https://www.linkedin.com/in/baturgultekin/)

**E-mail:** baturgultekin@sabanciuniv.edu , batur.gultekin@yale.edu

__________

### Zebrafish Primer Prep Guide

- Go to: https://zfin.org/
- Search for sa number of the gene
- Copy last 40 bases of the mutated sequence
- Go to: https://genome.ucsc.edu/cgi-bin/hgBlat
- Select Zebrafish genome and latest assebmly for the organism
- Paste the copied sequence part and submit
- Click on the browser of the targetted chromosome
- Zoom in to the mutation site at the end
- View in DNA form, add preferably 500 or 700 bases extra to both up and downstreams, all upper case and mask repeats to N. Get DNA, and copy the DNA seq.
- Go to: https://www.bioinformatics.nl/cgi-bin/primer3plus/primer3plus.cgi
- Change the task to Primer_List, primer size (18,19,21), primer tm (57,58,60), number to return (20) and gc clamp (preferably 2 or 1)
- Paste and submit the copied sequence
- Select the left and right primers

__________

### 2% Agarose Gel

Measure 3g of agarose
- Mix agarose powder with 150mL 1xTAE in a microwavable flask
- Microwave for 1-3 min until the agarose is completely dissolved (but do not overboil the solution, as some of the buffer will evaporate and thus alter the final percentage of agarose in the gel.
- Add ethidium bromide (EtBr) to a final concentration of approximately 0.3-0.6 μg/mL (usually about 2-3 μl of lab stock solution per 100 mL gel) or 1Oμl GreenGlow per 100mL TAE Agorose mix.

__________

### DNA Isolation 1x

Prepare 100 μl DNA Isolation Mix:
- 88 μl of nucleas-free water (non-DEPC-Treated)
- 10 μl of Kappa DNA Isolation Buffer
- 2 μl of Kappa DNA Isolation Enzyme

Add 100 μl of DNA Isolation mix to 96 well plate which contains the tissue
- Seal and mark the plate
- Run in the PCR machine

__________

### PCR 1x

Prepare 22 μl PCR Mix:
- 7 μl of nucleas-free water (non-DEPC-Treated)
- 1.25 μl of forward primer designed for the targetted region
- 1.25 μl of reverse primer designed for the targetted region
- 12.5 μl of Kappa PCR Enzyme

Fill 96 well plate wells with 22 μl PCR Mix
- Add 3 μl of DNA from the 1:10 diluted DNA Isolation product
- Seal and mark the plate
- Run in the PCR machine

__________

### Sequencing Preperation

Prepare 15 μl Sequencing Mix:
- 13 μl of nucleas-free water (non-DEPC-Treated)
- 2 μl of forward primer designed for the targetted region

Fill 96 well plate wells with 15 μl Sequencing Mix
- Add 3 μl of DNA from the PCR product
- Seal and mark the plate and put into a zip bag with the order info
- Place the plate in the Keck Sequencing Bucket 

__________

### TA Cloning 

**Before we start with the TA Cloning:** 
- We have to make PCR primers on both sides of the mutation site, to amplify a product 100-300nt long. (If you want to be even more sure, you can also make at least a nested primer at one end, so after you amplify the first product, you use it for nested PCR to reamplify to get an even cleaner PCR.)
- For PCR you need to use Taq, that makes A overhangs to the 3’ end of PCR products
- Then, use the PCR purification kit (for PCR cleanup I use the Qiagen PCR purification kit) to purify the product but resuspended in water instead of TE buffer. 

**We need to use one of the two kits below:**
- [TA Cloning™ Kit, with pCR™2.1 Vector, with or without competent cells](https://www.thermofisher.com/order/catalog/product/K202020)
- [TOPO™ TA Cloning™ Kit for Sequencing, with or without One Shot™ TOP10 Chemically Competent E. coli](https://www.thermofisher.com/order/catalog/product/K4575J10)
- The TOPO is a bit easier and faster to use, but both are good. The TA kit uses a ligase, takes 30-60min to ligate while the TOPO TA needs 15-30min to incubate. If you have any competent cells they should work. If not, perhaps get some cheap competent cells; almost any of them should work.


**Cloning:**
- Set up the following 3 μl TA reaction:
    - Fresh PCR product 1 μl
    - Salt solution 0.5 μl
    - Sterile water 1 μl
    - TOPO Vector 0.5 μl
- Incubate at 25 degrees celsius for 20 mins


**Transformation:**
- Take a bacteria vial and put it into ice w/o touching to the bacteria part
- Cool a tip and PCR tube as well
- Set up the following mix into pre-chilled PCR tube and tip
    - TA reaction 2.5 μl
    - E.coli cells 25 μl
- Incubate on ice for 5-10 mins
- Heat shock at 42 degrees celsius for 40 sec
- Place it back into ice
- Add 200 μl of S.O.C.
- Incubate it in shaker incubator for 30 mins at 37 degrees celsius
- Transfer it into an Eppendorf tube
- Centrifuge in high speed for 3 seconds
- Remove the supernatant
- Resuspend with 30 μl of water
- Spread it into a kanamycin plate
- Incubate it in incubator at 37 degrees celsius 

**Analyze Positive Clones**
- Pick 10 colonies and put it into 96 well plate
- Resuspend each colony with 100 μl of LB Kan
- Incubate it in shaking incubator for 30 min - 1 h at 37 degrees celsius
- Dilute a 3 μl of resuspension into 30 μl of water
- Incubate in PCR machine for 10 mins at 95 degrees celsius  
- Repeat the PCR with new colonies 
- Pick the positive clones according to comparison with initial PCR products gel electrophoresis.

__________

### Western Blot

![](wb1.png)
![](wb2.png)
![](wb3.png)
__________
