### IEEE_BSN_2019-EEG-Activity-Detection
Electroencephalography (EEG) is a noninvasive andinexpensive  means  of  monitoring  brain  activity.  Because  of  thelow-cost,   noninvasive   nature   of   EEG,   it   may   be   useful   forclassification  of  motor  movements  when  a  patient  controls  aprosthetic  device.  However,  due  to  the  high  velocity  nature  ofEEG recordings, the data used in such a classification are oftenlarge  and  may  take  a  long  time  to  process  on  a  local,  non-distributed  computer.  Here  we  explore  the  use  of  a  distributedcomputing architecture for storage and processing of EEG data.We  evaluate  the  classification  of  EEG  recordings  during  handmovements.  We  find that  processing  these  data on  a  distributedsystem results in much faster classification times (e.g., 726 secondsversus  3925  seconds)  without  limiting  accuracy  (e.g.,  AUC  of 0.85)
##### Cluster 1 Configs(1 Master, 3 Slaves)
Master - CPU cores: 8
Master - Memory: 32
Slave - CPU cores: 8
Slave - Memory: 32

##### Local Configs(1 Master, 0 Slaves)
Master - CPU cores: 4
Master - Memory: 16
