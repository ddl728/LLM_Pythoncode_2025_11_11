# 时间：2025-11-11
主要代码：
# 01-Agent_project_py
  ## 1.deepseek_create.py 
    ###(1)02-deepseek应用Deepseek的api接口，实现LLM本地化
# 03-Scene_analysis
  ## 1.scene_data_get_save.py
    ### (1)处理与服务器的持续通信。等待用户输入指令来决定何时发送数据。
    ### (2)数据包括工件坐标、四元数数据及尺寸；机器人基座的坐标及四元数数据
    ### (3)永久存储到"scene_data.json"中
    ### (4)SON存储四元数数据顺序[W、X、Y、Z]
  ## 2.calculate_relative_pose.py
    ### (1)将得到机器人基座位姿和工件的位姿，计算工件相对于机器人的相对位姿(坐标+四元数)，最后用于机器人动作脚本参数的输入
