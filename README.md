# Slave_basketball_arm_controller
This is the second version of the basketball arm controller(SLAVE).
<h2>第二代篮球机器人铲子控制</h2>
<p><font size="10px">增加速度</font></p>
<p>
    <ul>
        <li>ff ff 03 00 01 01 05	弹射shot</li>
        <li>ff ff 02 00 02 01 01 06	铲球得球并落下get_ball</li>
        <li>ff ff 02 00 02 01 02 07	铲球保持get_hold_ball</li>
		<li>ff ff 02 00 02 01 03 08	保持处得球并落下get_from_hold</li>
		<li>ff ff 02 00 02 01 04 09	从最高处落下high_down</li>
		<li>ff ff 02 00 02 01 05 0A	上升到最高high_lift</li>
		<li>ff ff 02 00 02 01 06 0B	保持处落下down_from_hold</li>
    </ul>
		<li>注意：</li>
			<ul>
				<li>调节TIM8的占空比即可调节铲子速度</li>
				<li>务必清楚驱动盒侧面目6个拨码开关的作用，目前动盒的拨码设置为 1，2 OFF，3，4 ON 5，6 OFF</li>
				<li>串口不需要回复数据</li>
			</ul>
</p>
