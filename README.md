# stm32_fft_led

2018年刚毕业时搞得玩用做得个小东西，stm32采样mp3音频，经fft用led显示频谱。

https://www.bilibili.com/video/BV1as41177af/?vd_source=3d543d7f8dc7a55028b4851436750164


顺便给些改建的建议
1、原先是用延时扫描的方式实现的Pmw，来改变亮度的效果。可以直接用硬件pmw。
2、软件上增加一些过滤，防止视频中同时闪烁的情况。
