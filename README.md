# you-lowcode
低代码平台

# 适用场景
> 低代码平台没有统一规范，要么大二全（操作复杂，维护成本高），要么小而精（操作简单，适用场景单一）
因此，我们需要根据不同的业务场景，设计不同的低代码平台。

网上现有的低代码平台，主要适用于以下场景：
- 表单收集页（如：问卷调查，用户反馈收集等）
- 海报
- 活动运营
- 中后台


> 当前项目目标是：**操作简单**、**易维护**、**性能好**， 适用于以下场景：
- 表单收集页
- 海报

# 实现方案
### 组成模块
低代码主要分为三个模块
- 左边：物料选择
- 中间：可视化编辑器
- 右边：物料配置栏

### 数据结构
> 低代码平台核心就是根据数据渲染页面，在不同平台展示，数据结构决定了平台的 **可扩展性**、**可维护性**、**性能**

#### 物料数据结构
``` typescript
// 基础属性
export interface IMaterialBase {
}
// 特有属性
export interface IMaterial {
}
```
#### 低代码平台数据结构

# 技术栈
vite + vue3 + typescript + element-ui + unocss

# 依赖
- node 18+

# 本地运行 {.tabset}
```typescript
// yarn
yarn
yarn dev

// npm
npm install
npm run dev

// pnpm
pnpm install
pnpm run dev
```

# 功能点
