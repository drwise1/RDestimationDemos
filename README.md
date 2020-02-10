# RDestimationDemos
RD estimation Demos are presented
1. Using the exe files in "Executable files for VTM-5.0",
   you can obtain the following files as the results of encoding:
   Ex) BlowingBubbles sequence
   a) log_BlowingBubbles_Q27_100_FRM_TC_CU_level_MSE_PSNR_rate_VTM.txt -> 1st column = PSNR, 2nd column = MSE, 3rd column = rate
   b) Transformed Coeffs of each CU.txt -> 16 columns indicate 'Transform coefficient values ranged from -512 to 512', 'CU128x128','CU64x64','CU32x32','CU16x16', 'CU8x8', 'CU4x4','CU64x32 or CU32x64','CU64x16 or CU16x64',
   'CU64x8 or CU8x64','CU32x16 or CU16x32', 'CU32x8 or CU8x32','CU32x4 or CU4x32','CU16x8 or CU8x16','CU16x4 or CU4x16','CU8x4 or CU4x8', 'single PDF'
   c) in order to execute the encoding, you need to execute the batch file "encode_BlowingBubbles_intra.bat".

2. Using the exe files in "Executable files for Matlab" and the above text data files after encoding VTM-5.0,
   you can obtain the RD estimation results for each sequences. Make sure that the '*.exe' file and corresponding '*.txt' data files are located in the same folder.
   
3. Yuv files needed to encode the VTM-5.0 are not included in this folder.
