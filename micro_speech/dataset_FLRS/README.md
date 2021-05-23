This 'dataset_FLRS' data set contains Mandarin audio file (.wav) recorded by myself using Arduino Nano 33 BLE Sense on [Edge Impulse Studio](https://studio.edgeimpulse.com/).

## Audio data
This audio data set is recorded with Edge Impulse Studio on Arduino Nano 33 BLE Sense with sampling rate of 16,000 and duration of one second, 16 bits per sample, mono channel.


## File naming convention
The data set file naming convention defined by Edge Impulse is using file name prior to the dot '.' as the label. For test data, I add extra 'test' right after the dot to distinguish the test data from train data, which is easier for me to tell the differences.


## Labels
This data set contains 4 labels (forward - 前進, left - 左, right - 右, stop - 停), with the following file structure

## File tructure  
dataset_FLRS   
&nbsp;&nbsp;&nbsp;&nbsp;|- Train_data  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- forward.xxxx.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- forward.yyyy.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- left.zzzz.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- left.mmmm.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- right.nnnn.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- right.pppp.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- stop.qqqq.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- stop.wwww.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;|- Test_data  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- forward.test.xxyy.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- left.test.yyzz.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- right.test.zzmm.wav  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;....  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|- stop.test.mmnn.wav   