# 实现步骤

1. 进行地址各个字段的分解
2. 计算Cache各个参数，选择大小合理的Block RAM，创建IP核并实例化
3. 编写命中判断的组合逻辑
4. 设计缺失处理的状态机（不局限于Moore或Mealy，也不局限于我们提供的几个状态，可以自由发挥）
5. 自己编写Testbench，验证相关功能正确性。
6. 使用提供的`all_sim.v`测试模块进行测试、调试，根据输出的调试信息，定位错误点。