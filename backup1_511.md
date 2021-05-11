## gedit keeps crashing, save current terminal work/locations and reboot

molecularecology@Chimborazo:/media/Summit/88_fastq/cleaned/AUG_GAMS/test_vcf_merge$ 
(test, running on chtc in genotypes, can close)


molecularecology@Chimborazo:/media/Summit/CHTC/staging/Modern_Museum/fastqs$
(about to rerun sfs in angsd here with new sites file: agenic_regions_FKS.list

molecularecology@Chimborazo:/media/Summit/zach_vg/minigraph$
(location for a ton of important files)
  molecularecology@Chimborazo:/media/Summit/zach_vg/minigraph/tajD_sig_cyp4g15/new_sig_part1$
   (tajD sig file for..title)
   

molecularecology@Chimborazo:/media/Summit/plink/Scaffolds_SNPs$
(structural variant files)

molecularecology@Chimborazo:/media/Summit/88_fastq/cleaned/Linear_Bams/Results_TajD
(sliding window TajD for SV chapter 2; also dummy test for structure plotting: structure_57)


molecularecology@Chimborazo:/media/Summit/CHTC/staging/Modern_Museum/fastqs/RAiSD/raisd-master$
(output for selective sweep windows, this crashed texteditor all_WI_25_run_51_output.txt)

$$ for j in `ls  RAiSD_Report.WI*25*run_51* | sed 's/RAiSD_Report.WI_25_run_51.//g'`; do for z in `ls RAiSD_Report.WI*25*run_51*`; do if [[ "$z" == *"$j" ]]; then sed "s/^/$j=/g" "$z" > tigs_"$z";fi; done; done
