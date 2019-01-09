Convert csv to db
Downloaded rufuspollock's csv2sqlite python script
Opened Anaconda prompt
navigated directory to github/csv2sqlite
Used commands<read this section as everything after the '(base)' designation:
(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/Cleaned/DST25_cleaned.csv HERD2016.db [Fed_Financed_HERD_by_Agency_2016]

(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/Cleaned/DST_24_cleaned.csv HERD2016.db [Fed_Financed_HERD_by_Source_2016]

(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/Cleaned/DST_22_cleaned.csv HERD2016.db [HERD_by_RD_Field_2016]

(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/Cleaned/DST_21_cleaned.csv HERD2016.db [HERD_by_Source_2016]

Creates database 'HERD2016.db' with 4 tables
-Went to create a groups database, used commands:


(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/UnitIDs_and_Groups/AAUwid.csv R1_AAU_Peers.db [AAU]

(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/UnitIDs_and_Groups/R1wid.csv R1_AAU_Peers.db [R1]

(base) C:\Users\cgdeer\Documents\GitHub\csv2sqlite>python csv2sqlite.py c:/users/cgdeer/documents/GitHub/HERD_analysis/Data/UnitIDs_and_Groups/ABOR_PEERS_ASU_UA_NAUwid.csv R1_AAU_Peers.db [Peer]

Creates a database 'R1_AAU_Peers.db' with 3 tables