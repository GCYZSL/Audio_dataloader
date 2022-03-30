# Audio_dataloader
Prepare audio data and the dataloader

1. Data download at https://www.openslr.org/12 <br>
train-clean-100.tar.gz [6.3G]   (training set of 100 hours "clean" speech )   Mirrors: [US]   [EU]   [CN]  
train-clean-360.tar.gz [23G]   (training set of 360 hours "clean" speech )   Mirrors: [US]   [EU]   [CN]  
train-other-500.tar.gz [30G]   (training set of 500 hours "other" speech )   Mirrors: [US]   [EU]   [CN]  

2. Run prep_librispeech.py for data preparation.<br>
   the path of the data should be changed to your local directory in line 79: librispeech100_path.<br>
   the output file name is in line 80: 'librispeech_tr100_cut'.

3. Run run_dataloader to test. <br>
   input_json in line 43 should be changed to the name of the output file generated in step 2.
