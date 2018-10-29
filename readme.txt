NAME: EVPT_新架构VCU配置文件

GROUP1 整车控制器
GROUP2 电池管理系统
GROUP3 电机控制器/DCDC
GROUP4 仪表


/begin ID 0x1F0A0001
    /begin monitored_VCU 钥匙信号
        StartByte 0
        StartBit 0
        Length_bit 4
        physical range
        unit       
        /begin conversion
        table
              0000 OFF yellow
              0011 ON green
              1100 START red
        /end conversion      
    /end monitored
    /begin monitored_VCU 档位信号
        StartByte 0
        StartBit 4
        Length_bit 4
        physical range
        unit       
        /begin conversion
        table
              0000 IDEL yellow
              0011 FRONT green
              1100 BACK red
        /end conversion      
    /end monitored
    /begin monitored_VCU 加速踏板开度
        StartByte 1
        StartBit 8
        Length_bit 8
        physical range 0 100
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 制动踏板开度
        StartByte 2
        StartBit 16
        Length_bit 8
        physical range 0 100
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 蓄电池电压
        StartByte 3
        StartBit 24
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 0.1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障码上报序号
        StartByte 5
        StartBit 40
        Length_bit 12
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障1
        StartByte 6
        StartBit 52
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障2
        StartByte 6
        StartBit 53
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障3
        StartByte 6
        StartBit 54
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障4
        StartByte 6
        StartBit 55
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障5
        StartByte 7
        StartBit 56
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障6
        StartByte 7
        StartBit 57
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障7
        StartByte 7
        StartBit 58
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/begin monitored_VCU 故障8
        StartByte 7
        StartBit 59
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/begin monitored_VCU 故障9
        StartByte 7
        StartBit 60
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/begin monitored_VCU 故障10
        StartByte 7
        StartBit 61
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/begin monitored_VCU 故障11
        StartByte 7
        StartBit 62
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/begin monitored_VCU 故障12
        StartByte 7
        StartBit 63
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OK green
              1 Fault red
        /end conversion      
    /end monitored
/end ID
/begin ID 0x1F0A0002
    /begin monitored_VCU VCU状态
        StartByte 0
        StartBit 0
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU VCU的操作进度
        StartByte 1
        StartBit 8
        Length_bit 4
        physical range
        unit       
        /begin conversion
        table
              0001 断电 red
              0010 上电 green
              0011 READY yellow
        /end conversion      
    /end monitored
    /begin monitored_VCU 爬坡过程踩制动标识
        StartByte 2
        StartBit 16
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 前进有效标识
        StartByte 2
        StartBit 17
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 倒车有效标识
        StartByte 2
        StartBit 18
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 踩刹车挂挡有效标识
        StartByte 2
        StartBit 19
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 加速优先标识
        StartByte 2
        StartBit 20
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 巡航有效标识
        StartByte 2
        StartBit 21
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 爬坡有效标识
        StartByte 2
        StartBit 22
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored    
    /begin monitored_VCU 滑行有效标识
        StartByte 2
        StartBit 23
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Invalid red
              1 valid green 
        /end conversion      
    /end monitored
    /begin monitored_VCU 放电功率调整系数
        StartByte 4
        StartBit 32
        Length_bit 8
        physical range 0 100
        unit       
        /begin conversion
        Unsigned
              a 0.01
              b 0
        /end conversion      
    /end monitored
/begin monitored_VCU 充电功率调整系数
        StartByte 4
        StartBit 32
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 0.01
              b 0
        /end conversion      
    /end monitored
/begin monitored_VCU 最大放电功率
        StartByte 5
        StartBit 40
        Length_bit 12
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
/begin monitored_VCU 最大充电功率
        StartByte 6
        StartBit 52
        Length_bit 12
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
/end ID
/begin ID 0x1F0A0003
    /begin monitored_VCU MCU调整系数
        StartByte 0
        StartBit 0
        Length_bit 7
        physical range
        unit       
        /begin conversion
        Unsigned
              a 0.01
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 电机过敏系数
        StartByte 0
        StartBit 7
        Length_bit 9
        physical range
        unit       
        /begin conversion
        Unsigned
              a 0.01
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 电机最大扭矩
        StartByte 2
        StartBit 16
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 电机最大倒挡扭矩
        StartByte 4
        StartBit 32
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障断电标识
        StartByte 6
        StartBit 48
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障禁止行车标识
        StartByte 6
        StartBit 49
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障跛行标识
        StartByte 6
        StartBit 50
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障只允许端行标识
        StartByte 6
        StartBit 51
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障禁止端行标识
        StartByte 6
        StartBit 52
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red 
        /end conversion      
    /end monitored   
   /begin monitored_VCU 故障限制车速标识
        StartByte 6
        StartBit 53
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
               0 Normal green
               1 Fault  red 
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障限制BMS放电功率标识
        StartByte 6
        StartBit 54
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障限制MCU功率标识
        StartByte 6
        StartBit 55
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障限制BMS充电功率标识
        StartByte 7
        StartBit 56
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障禁止能量回收标识
        StartByte 7
        StartBit 57
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 故障点亮故障灯标识
        StartByte 7
        StartBit 58
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU MCU总线脱离故障
        StartByte 7
        StartBit 59
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU BMS总线脱离故障
        StartByte 7
        StartBit 60
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
    /begin monitored_VCU DCDC总线脱离故障
        StartByte 7
        StartBit 61
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 Normal green
              1 Fault  red
        /end conversion      
    /end monitored
/end ID
/begin ID 0x1F0A0004
    /begin monitored_VCU 低边驱动1（pin5）
        StartByte 0
        StartBit 0
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动2（pin4）
        StartByte 0
        StartBit 1
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动3（pin2）
        StartByte 0
        StartBit 2
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动4（pin1）
        StartByte 0
        StartBit 3
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动5（pin24）
        StartByte 0
        StartBit 4
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动6（pin43）
        StartByte 0
        StartBit 5
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动7（pin23）
        StartByte 0
        StartBit 6
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动8（pin42）
        StartByte 0
        StartBit 7
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动9（pin81）
        StartByte 1
        StartBit 8
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动10（pin62）
        StartByte 1
        StartBit 9
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动11
        StartByte 1
        StartBit 10
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动12
        StartByte 1
        StartBit 11
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动13
        StartByte 1
        StartBit 12
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动14
        StartByte 1
        StartBit 13
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动15
        StartByte 1
        StartBit 14
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动16
        StartByte 1
        StartBit 15
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动17
        StartByte 2
        StartBit 16
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 低边驱动18
        StartByte 2
        StartBit 17
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 高边驱动1（pin7）
        StartByte 2
        StartBit 18
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 高边驱动2（PIN26）
        StartByte 2
        StartBit 19
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 高边驱动3（pin53）
        StartByte 2
        StartBit 20
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU 高边驱动4（pin72）
        StartByte 2
        StartBit 21
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU lamp1（pin79）
        StartByte 3
        StartBit 24
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU lamp2（pin60）
        StartByte 3
        StartBit 25
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN6_Mp
        StartByte 4
        StartBit 32
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN18_Mp
        StartByte 4
        StartBit 33
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN19_Mp
        StartByte 4
        StartBit 34
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN20_Mp
        StartByte 4
        StartBit 35
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN21_Mp
        StartByte 4
        StartBit 36
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN37_Mp
        StartByte 4
        StartBit 37
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN38_Mp
        StartByte 4
        StartBit 38
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored

    /begin monitored_VCU IO_swtPIN39_Mp
        StartByte 4
        StartBit 39
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN59_Mp
        StartByte 5
        StartBit 40
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN77_Mp
        StartByte 5
        StartBit 41
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN78_Mp
        StartByte 5
        StartBit 42
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtKeyOn_Mp
        StartByte 5
        StartBit 43
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtCharge_Mp
        StartByte 5
        StartBit 44
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU key2_temp
        StartByte 5
        StartBit 45
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN60Read_Mp
        StartByte 5
        StartBit 46
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
    /begin monitored_VCU IO_swtPIN79Read_Mp
        StartByte 5
        StartBit 47
        Length_bit 1
        physical range
        unit       
        /begin conversion
        table
              0 OFF green
              1 ON  red
        /end conversion      
    /end monitored
/end ID
/begin ID 0x18E5A2A6
    /begin monitored_VCU 软件版本小号
        StartByte 0
        StartBit 0
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU 软件版本大号
        StartByte 1
        StartBit 8
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU 软件版本车型编号
        StartByte 2
        StartBit 16
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored     
    /begin monitored_VCU 软件版本厂家编号
        StartByte 3
        StartBit 24
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored 
    /begin monitored_VCU 算法层版本1
        StartByte 4
        StartBit 32
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored 
    /begin monitored_VCU 算法层版本2
        StartByte 5
        StartBit 40
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored 
    /begin monitored_VCU 算法层版本3
        StartByte 6
        StartBit 48
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored 
/end ID
/begin ID 0x1F0A0006
    /begin monitored_VCU AD_Value_PIN68
        StartByte 2
        StartBit 16
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU AD_Value_PIN49
        StartByte 4
        StartBit 32
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU Cr_uBatPackVol
        StartByte 6
        StartBit 48
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
/end ID
/begin ID 0x1F0A0007
    /begin monitored_VCU Tc_trqRequirment_MP
        StartByte 0
        StartBit 0
        Length_bit 16
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion      
    /end monitored
    /begin monitored_VCU Eaf_stTest
        StartByte 2
        StartBit 16
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU BUSOFF
        StartByte 3
        StartBit 24
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU Cr_stMCUErrorLevel
        StartByte 4
        StartBit 32
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU Cr_stBMSErrorLevel
        StartByte 5
        StartBit 40
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU Ea_stKeyState
        StartByte 6
        StartBit 48
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
    /begin monitored_VCU PIN32脚驻车制动状态
        StartByte 7
        StartBit 56
        Length_bit 8
        physical range
        unit       
        /begin conversion
        Unsigned
              a 1
              b 0
        /end conversion 
    /end monitored
/end ID