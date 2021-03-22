# Speech-Simulation-Tools
语音增强领域的相关数据仿真工具和方法汇总--持续更新

1：MASG, https://github.com/vipchengrui/MASG
功能实现：房间声学中的麦克风阵列语音发生器(MASG)，仿真室内环境下的麦克风阵列采集数据

2：gpuRIR, https://github.com/DavidDiazGuerra/gpuRIR
功能实现：gpu加速的RIR仿真

3：StoRIR，https://github.com/SRPOL-AUI/storir
功能实现：一种不同于RIR的随机房间脉冲响应生成方法，用于机器学习应用中的音频数据增强，不需要知道房间尺寸和声源位置

4：RIR，https://github.com/ehabets/RIR-Generator  
功能描述：基于matlab版本的RIR生成算法仿真  

5: DNS-Challenge,https://github.com/microsoft/DNS-Challenge  
功能实现：微软开源的DNS挑战赛的数据和仿真脚本，可以直接进行数据的仿真，包括加混响和噪声  

6：ConferenceSpeech2021,https://github.com/ConferencingSpeech/ConferencingSpeech2021/tree/master/eval  
功能实现：腾讯组织的麦克风阵列语音增强比赛，其中的eval可以批处理生成pesq,stoi，si-sdr等客观评价指标，并输出文件，非常有用。  
注：非常好的多通道仿真数据生成脚本，可以根据干净语音、噪声和冲击响应生成响应的多通道数据，包括混响参考数据和非混响参考数据，以及对应的带噪语音数据。
