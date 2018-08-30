#BIMAP

JGR2018 contains the processed BIMAP data presented in 
Shao et. al. "Broadband RF interferometric mapping and polarization (BIMAP) observations of lightning discharges: revealing new physics insights into breakdown processes"

The processed data is stored in IDL save files for Interfermetric and Polarization analysis, and can be accessed as in the example below.  

IDL> restore, filename='Intf_Processed_p3_LNL0_EX1S-Ch0_20170606_183553_361362121.dat.sav'
IDL> help
% At $MAIN$          
FA              DOUBLE    = Array[1900000]
GA              DOUBLE    = Array[1900000]
POLEW           DOUBLE    = Array[1900000]
POLNS           DOUBLE    = Array[1900000]
RF0_1           DOUBLE    = Array[1900000]
RF4             FLOAT     =       0.00000
RFE             DOUBLE    = Array[1900000]
RFN             DOUBLE    = Array[1900000]
T_BASE1         DOUBLE    = Array[1900000]
T_BASE2         DOUBLE    = Array[1900000]


IDL> restore, filename='Pola_Processed_p3_LNL0_EX1S-Ch0_20170606_183553_361362121.dat.sav'
IDL> help
% At $MAIN$          
AZ              FLOAT     = Array[368270]
AZ_ERR          FLOAT     = Array[368270]
EL              DOUBLE    = Array[368270]
EL_ERR          FLOAT     = Array[368270]
INTF_POWER      FLOAT     = Array[368270]
PEAK_XC123_ARR  FLOAT     = Array[368270]
P_AR            FLOAT     = Array[237475, 12]
P_FREQ          DOUBLE    = Array[12]
P_POWER         FLOAT     = Array[237475, 12]
P_RATIO         FLOAT     = Array[237475, 12]
P_TAU           FLOAT     = Array[237475, 12]
T_INTF          DOUBLE    = Array[368270]
T_POLA          DOUBLE    = Array[237475]
X               FLOAT     = Array[368270]
X_ERR           FLOAT     = Array[368270]
Y               FLOAT     = Array[368270]
Y_ERR           FLOAT     = Array[368270]
