# Rudder tracking face



简介:	二维云台人脸追踪

作者:	BriMon

邮箱:	1610937885@qq.com

平台:	K210

舵机:	SG90

语言:	micro python



使用说明:	将 face_model_at_0x300000 存入k210flash的0x300000位置

针对不同的云台，可能需要修改占空比(duty)的允许范围，以及摄像头、LCD和PWM输出的方向。