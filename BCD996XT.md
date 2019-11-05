# BCD996XT扫描接收机使用说明

## 按键功能说明

- 三个旋钮
    - 左下: 
        - 旋转: 开关，音量
        - 按下: 背光调节
    - 左上:
        - 旋转: 静噪(SQL)水平
        - 按下: Close Call近场扫描模式切换: OFF/PRI(优先)/DND(勿扰)
    - 右侧:
        - 旋转: 上下选择, 频率加减, 方向上下
        - 按下: 第二功能键, 屏幕上相应亮起[F]标志, 再按其他键为第二功能
- 屏幕右边一排
    - PRI: 优先模式
    - WX: 天气频道，国内没用
    - GPS: 连接COM口GPS后使用
    - MENU: 
        - 打开当前模式下的菜单
        - 若进入子菜单, 按一次返回上级菜单
    - L/O: 
        - Lock out, 即排除当前频率或频道, 下次直接跳过
        - 进入菜单或频率输入模式时, 退出当前菜单
- 数字区
    - 0-9: 数字键
        - 第二功能[按大旋钮后]: 6-显示模式, 7-衰减器, 9-解调模式(FM/NFM/AM)
        - 其余未知
    - .: NO 取消/小数点
    - E: YES 确认
- 右侧两个
    - SCAN/SEARCH: 切换扫描和搜索两个模式
        - SCAN: 在预存频道的选中范围内扫描, 即轮询已知频道
        - SEARCH(第二功能): 未知频道, 根据设置的上下限依次扫描, 有信号则停下
    - HOLD/RESUME:
        - 按一下HOLD住, 即频率不在变, 停止扫描或搜索, 再按一下放开, 继续

## 菜单

这里就主要几个功能说明下, 未说明的是我不清楚或很简单的, 不再赘述

- Program System: 编辑扫描系统(System), 即相当于几套扫描配置, 彼此独立
    - 新建时选Conventional 是普通模拟, 其余几个是集群, 我没玩过
    - 可设置该系统的快捷键, 扫描延迟, 语音增益等
    - 系统(System)下可设置组, 组内包含若干频率
    - 扫描时临时储存的频道, 会存在Qck Save Cnv Sys中
    - 一个System中包含了扫描和搜索的配置
    - 若需要只扫一个系统, 需要将其余系统屏蔽(Lockout)掉
- Program Location: 编辑地点扫描, 没用
- Srch/CloCall Opt: 搜索/近场扫描选项
- Search for: 搜索模式
    - Service Search: 服务搜索, 美国预定义了一些公共服务的频率范围
    - Edit Service: 每个服务的配置
    - Custom Search: 直接进入自定义搜索
    - Edit Custom: 设置自定义扫描的段
        - Edit Srch Limit: 设置上下限
        - Delay: 信号消失后等待时间
        - Modulation: 调制方式
        - Attenuator: 衰减器
        - Step: 扫描步长
- Close Call: 近场扫描
    - Close Call Only: 仅近场
    - Set CC Alert: 告警方式
    - Set CC Bands: 近场扫描频段
- Setting: 系统设置

