NAME: EVPT_�¼ܹ�VCU�����ļ�

GROUP1 ����������
GROUP2 ��ع���ϵͳ
GROUP3 ���������/DCDC
GROUP4 �Ǳ�


/begin ID 0x1F0A0001
    /begin monitored_VCU Կ���ź�
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
    /begin monitored_VCU ��λ�ź�
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
    /begin monitored_VCU ����̤�忪��
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
    /begin monitored_VCU �ƶ�̤�忪��
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
    /begin monitored_VCU ���ص�ѹ
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
    /begin monitored_VCU �������ϱ����
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
    /begin monitored_VCU ����1
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
    /begin monitored_VCU ����2
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
    /begin monitored_VCU ����3
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
    /begin monitored_VCU ����4
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
    /begin monitored_VCU ����5
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
    /begin monitored_VCU ����6
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
    /begin monitored_VCU ����7
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
/begin monitored_VCU ����8
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
/begin monitored_VCU ����9
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
/begin monitored_VCU ����10
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
/begin monitored_VCU ����11
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
/begin monitored_VCU ����12
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
    /begin monitored_VCU VCU״̬
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
    /begin monitored_VCU VCU�Ĳ�������
        StartByte 1
        StartBit 8
        Length_bit 4
        physical range
        unit       
        /begin conversion
        table
              0001 �ϵ� red
              0010 �ϵ� green
              0011 READY yellow
        /end conversion      
    /end monitored
    /begin monitored_VCU ���¹��̲��ƶ���ʶ
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
    /begin monitored_VCU ǰ����Ч��ʶ
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
    /begin monitored_VCU ������Ч��ʶ
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
    /begin monitored_VCU ��ɲ���ҵ���Ч��ʶ
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
    /begin monitored_VCU �������ȱ�ʶ
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
    /begin monitored_VCU Ѳ����Ч��ʶ
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
    /begin monitored_VCU ������Ч��ʶ
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
    /begin monitored_VCU ������Ч��ʶ
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
    /begin monitored_VCU �ŵ繦�ʵ���ϵ��
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
/begin monitored_VCU ��繦�ʵ���ϵ��
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
/begin monitored_VCU ���ŵ繦��
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
/begin monitored_VCU ����繦��
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
    /begin monitored_VCU MCU����ϵ��
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
    /begin monitored_VCU �������ϵ��
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
    /begin monitored_VCU ������Ť��
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
    /begin monitored_VCU �����󵹵�Ť��
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
    /begin monitored_VCU ���϶ϵ��ʶ
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
    /begin monitored_VCU ���Ͻ�ֹ�г���ʶ
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
    /begin monitored_VCU �������б�ʶ
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
    /begin monitored_VCU ����ֻ������б�ʶ
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
    /begin monitored_VCU ���Ͻ�ֹ���б�ʶ
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
   /begin monitored_VCU �������Ƴ��ٱ�ʶ
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
    /begin monitored_VCU ��������BMS�ŵ繦�ʱ�ʶ
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
    /begin monitored_VCU ��������MCU���ʱ�ʶ
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
    /begin monitored_VCU ��������BMS��繦�ʱ�ʶ
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
    /begin monitored_VCU ���Ͻ�ֹ�������ձ�ʶ
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
    /begin monitored_VCU ���ϵ������ϵƱ�ʶ
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
    /begin monitored_VCU MCU�����������
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
    /begin monitored_VCU BMS�����������
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
    /begin monitored_VCU DCDC�����������
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
    /begin monitored_VCU �ͱ�����1��pin5��
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
    /begin monitored_VCU �ͱ�����2��pin4��
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
    /begin monitored_VCU �ͱ�����3��pin2��
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
    /begin monitored_VCU �ͱ�����4��pin1��
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
    /begin monitored_VCU �ͱ�����5��pin24��
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
    /begin monitored_VCU �ͱ�����6��pin43��
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
    /begin monitored_VCU �ͱ�����7��pin23��
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
    /begin monitored_VCU �ͱ�����8��pin42��
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
    /begin monitored_VCU �ͱ�����9��pin81��
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
    /begin monitored_VCU �ͱ�����10��pin62��
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
    /begin monitored_VCU �ͱ�����11
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
    /begin monitored_VCU �ͱ�����12
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
    /begin monitored_VCU �ͱ�����13
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
    /begin monitored_VCU �ͱ�����14
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
    /begin monitored_VCU �ͱ�����15
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
    /begin monitored_VCU �ͱ�����16
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
    /begin monitored_VCU �ͱ�����17
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
    /begin monitored_VCU �ͱ�����18
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
    /begin monitored_VCU �߱�����1��pin7��
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
    /begin monitored_VCU �߱�����2��PIN26��
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
    /begin monitored_VCU �߱�����3��pin53��
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
    /begin monitored_VCU �߱�����4��pin72��
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
    /begin monitored_VCU lamp1��pin79��
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
    /begin monitored_VCU lamp2��pin60��
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
    /begin monitored_VCU ����汾С��
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
    /begin monitored_VCU ����汾���
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
    /begin monitored_VCU ����汾���ͱ��
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
    /begin monitored_VCU ����汾���ұ��
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
    /begin monitored_VCU �㷨��汾1
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
    /begin monitored_VCU �㷨��汾2
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
    /begin monitored_VCU �㷨��汾3
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
    /begin monitored_VCU PIN32��פ���ƶ�״̬
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