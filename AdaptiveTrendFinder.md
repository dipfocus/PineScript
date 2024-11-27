In the dynamic landscape of financial markets, the Adaptive Trend Finder (log) stands out as an example of precision and professionalism. This advanced tool, equipped with a unique feature, offers traders a sophisticated approach to market trend analysis: the choice between automatic detection of the long-term or short-term trend channel.

**Key Features**:

1. Choice Between Long-Term or Short-Term Trend Channel Detection: Positioned first, this distinctive feature of the Adaptive Trend Finder (log) allows traders to customize their analysis by choosing between the automatic detection of the long-term or short-term trend channel. This increased flexibility adapts to individual trading preferences and changing market conditions.

2. Autonomous Trend Channel Detection: Leveraging the robust statistical measure of the Pearson coefficient, the Adaptive Trend Finder (log) excels in autonomously locating the optimal trend channel. This data-driven approach ensures objective trend analysis, reducing subjective biases, and enhancing overall precision.

3. Precision of Logarithmic Scale: A distinctive characteristic of our indicator is its strategic use of the logarithmic scale for regression channels. This approach enables nuanced analysis of linear regression channels, capturing the subtleties of trends while accommodating variations in the amplitude of price movements.

4. Length and Strength Visualization: Traders gain a comprehensive view of the selected trend channel, with the revelation of its length and quantification of trend strength. These dual pieces of information empower traders to make informed decisions, providing insights into both the direction and intensity of the prevailing trend.

In the demanding universe of financial markets, the Adaptive Trend Finder (log) asserts itself as an essential tool for traders, offering an unparalleled combination of precision, professionalism, and customization. Highlighting the choice between automatic detection of the long-term or short-term trend channel in the first position, this indicator uniquely caters to the specific needs of each trader, ensuring informed decision-making in an ever-evolving financial environment.

**Prompt**:
```
请编写一个用于金融市场的自适应趋势检测器。这个检测器应具有以下功能：

1. 名称与设置：
- 指标名称为 "Adaptive Trend Finder (log)"，并且应该覆盖在价格图表上。
- 最大回溯柱数量为 1200。
2. 功能要求：
- 趋势通道检测：根据不同的周期长度，计算趋势通道的上边界、中线、下边界，通道范围通过价格的标准差计算得到。
- 自动选择最佳周期：通过计算不同周期的皮尔森相关系数来自动选择趋势最强的周期。
- 趋势强度显示：提供趋势强度描述，包括 "Extremely Weak" 到 "Ultra Strong" 等级。
- 年化回报率计算：根据趋势的周期和价格变化，计算年化回报率，适用于日线和周线时间周期。
3. 用户自定义设置：
- 通道设置：允许用户选择是否使用长周期通道，以及设定偏差倍数、颜色、透明度、线条样式等。
- 中线设置：允许用户自定义中线的颜色、透明度、宽度和样式。
- 表格显示设置：允许用户选择是否显示自动选择的周期、趋势强度、皮尔森相关系数以及年化回报率等信息。
4. 输出要求：
- 通道绘制：绘制上边界线、中线和下边界线，并填充上下边界之间的区域。
- 表格显示：在图表上展示自动选择的周期长度、趋势强度、年化回报率等信息。
5. 逻辑流程：
- 使用线性回归计算各个周期的斜率、截距等指标。
- 根据皮尔森相关系数选择最强趋势周期，并绘制通道。
- 根据用户的输入设置调整绘图样式和显示内容。
6. 其他要求：
- 使用对数价格来计算趋势，以使得数据更加平滑且适用于大范围的价格波动。
- 提供良好的代码结构和注释，以便于理解和后续修改。
```