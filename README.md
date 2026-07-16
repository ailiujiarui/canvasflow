# CanvasFlow

CanvasFlow 是一个使用 React、TypeScript、Vite 和 React Flow 构建的可视化工作流编辑器，用于展示编辑器级交互和明确的流程校验。

## 已实现

- 无限画布平移、缩放、小地图和适应视图
- 开始、HTTP 请求、条件判断、数据转换、延时等待和输出结果节点
- 节点创建、选择、连线、删除和配置编辑
- 撤销/重做、保存状态和试运行状态
- 开始节点、配置完整性和不可达节点校验
- 可操作的校验面板和逐节点模拟运行状态

## 运行

```bash
npm install
npm run dev
npm run build
```

当前版本为客户端演示，试运行使用受控模拟状态，不执行任意 JavaScript，也不发起不受限制的网络请求。
