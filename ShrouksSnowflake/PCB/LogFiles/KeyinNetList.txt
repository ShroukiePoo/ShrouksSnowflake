;; V4.1.0
%net
%Prior=1

%page=Schematic1!BatteryLEDsFront
\$1N12_BatteryLEDsFront\    \LED100\-\2\ \R100\-\1\ 
\$1N15_BatteryLEDsFront\    \LED101\-\2\ \R101\-\1\ 
\$1N18_BatteryLEDsFront\    \LED102\-\2\ \R102\-\1\ 
\$1N21_BatteryLEDsFront\    \LED103\-\2\ \R103\-\1\ 
\$1N24_BatteryLEDsFront\    \LED104\-\2\ \R104\-\1\ 
\$1N27_BatteryLEDsFront\    \LED105\-\2\ \R105\-\1\ 
\+3VTop\    \BT100\-\1\ \R100\-\2\ \R101\-\2\ \R102\-\2\ \R103\-\2\ 
*  \R104\-\2\ \R105\-\2\ 
\GND\    \BT100\-\2\ \LED100\-\1\ \LED101\-\1\ \LED102\-\1\ \LED103\-\1\ 
*  \LED104\-\1\ \LED105\-\1\ 

%page=Schematic1!BatteryLEDsBack
\$1N12_BatteryLEDsBack\    \LED200\-\2\ \R200\-\1\ 
\$1N15_BatteryLEDsBack\    \LED201\-\2\ \R201\-\1\ 
\$1N18_BatteryLEDsBack\    \LED202\-\2\ \R202\-\1\ 
\$1N21_BatteryLEDsBack\    \LED203\-\2\ \R203\-\1\ 
\$1N24_BatteryLEDsBack\    \LED204\-\2\ \R204\-\1\ 
\$1N27_BatteryLEDsBack\    \LED205\-\2\ \R205\-\1\ 
\+3VBot\    \BT200\-\1\ \R200\-\2\ \R201\-\2\ \R202\-\2\ \R203\-\2\ 
*  \R204\-\2\ \R205\-\2\ 
\GND\    \BT200\-\2\ \LED200\-\1\ \LED201\-\1\ \LED202\-\1\ \LED203\-\1\ 
*  \LED204\-\1\ \LED205\-\1\ 

%Part
\SMTU_2477N-1-LF\    \BT100\ \BT200\ 
\VISHAYINTERTECHNOLOGIE_CRCW08052K00JNEA\    \R100\ \R101\ \R102\ \R103\ 
*  \R104\ \R105\ \R200\ \R201\ \R202\ \R203\ \R204\ \R205\ 
\WURTHELEKTRONIK_150060RS75000\    \LED100\ \LED101\ \LED102\ \LED103\ 
*  \LED104\ \LED105\ \LED200\ \LED201\ \LED202\ \LED203\ \LED204\ \LED205\ 
