---
title: "研一项目: 嵌入式数字网络分析仪的应用"
date: 2022-03-11T18:35:26+01:00
draft: false

weight: 40



---

# 项目简介 :


<p align = "justify"> 在本项目中，我们将使用以 RTL2832U 接收器为基础的树莓派 4 微控制器，在 Linux 环境下使用 buildroot 生成所需的系统文件。 我们需要通过 SSH 在 PC 和树莓派之间进行互连。 并在PC上安装所需的gnuradio 3.8软件和python3环境。 然后我们在PC的Gnu radio上绘制我们需要的模块，并生成对应的模块python代码。 最后将生成的代码上传到树莓派的系统文件中，让树莓派运行。 我们在 PC 上收到树莓派执行任务和生成的数据。 在项目结束时，我们将使用树莓派 4将指定频率的噪声传输到 GPIO4引脚上，通过DVB-T地面数码视讯广播接收，然后将信息传输到 PC 使用 GNU Radio 软件进行分析。 </p>


![projets](../../../projets/projet2.png )
