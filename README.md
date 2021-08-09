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
1：仿真训练所需数据时，给出干净语音，多通道冲击响应和噪声后，即可仿真生成多通道带噪混响语音；
2：训练时，默认为8通道数据，每个通道6s，配置时train.yaml中val_chun和train_chunk均为6



# Data Augmentation 数据增强  

### 2021-8-9
paper title: SpecMix : A Mixed Sample Data Augmentation method for Training withTime-Frequency Domain Features  
paper title: SpecMix：一种利用时频域特征训练的混合样本数据增强方法  
链接：https://arxiv.org/abs/2108.03020  
作者：Gwantae Kim,David K. Han,Hanseok Ko  
github： https://github.com/GT-KIM/specmix  
机构：Korea University, South Korea, Drexel University, USA  
备注：Accepted to interspeech 2021  

muda: https://github.com/bmcfee/muda https://muda.readthedocs.io/en/latest/  
SpecAugment: https://github.com/DemisEom/SpecAugment  

Facebook-Augly: https://github.com/facebookresearch/AugLy  
Introc: AugLy is a data augmentations library that currently supports four modalities (audio, image, text & video) and over 100 augmentations.   

Asteroid-team: https://github.com/asteroid-team/torch-audiomentations  
Introc:  Audio data augmentation in PyTorch. Inspired by audiomentations.  

Audiomentation: https://github.com/iver56/audiomentations  
Introc: A Python library for audio data augmentation. Inspired by albumentations（图像数据增强）.  
