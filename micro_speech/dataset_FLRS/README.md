This 'dataset_FLRS' data set contains Mandarin audio file (.wav) recorded by myself using Arduino Nano 33 BLE Sense on [Edge Impulse Studio](https://studio.edgeimpulse.com/).

## Audio data
This audio data set is recorded with Edge Impulse Studio on Arduino Nano 33 BLE Sense with sampling rate of 16,000 and duration of one second, 16 bits per sample, mono channel.


## File naming convention
The data set file naming convention defined by Edge Impulse is using file name prior to the dot '.' as the label. For test data, I add extra 'test' right after the dot to distinguish the test data from train data, which is easier for me to tell the differences.


## Labels
This data set contains 4 labels (forward - 前進, left - 左, right - 右, stop - 停), with the following file structure

## File tructure  
dataset_FLRS   
    |- Train_data  
        |- forward.xxxx.wav  
        |- forward.yyyy.wav  
        ....  
        |- left.zzzz.wav  
        |- left.mmmm.wav  
        ....  
        |- right.nnnn.wav  
        |- right.pppp.wav  
        ....  
        |- stop.qqqq.wav  
        |- stop.wwww.wav  
        ....  
    |- Test_data  
        |- forward.test.xxyy.wav  
        ....  
        |- left.test.yyzz.wav  
        ....  
        |- right.test.zzmm.wav  
        ....  
        |- stop.test.mmnn.wav   