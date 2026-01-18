# I18n 迁移报告

## 📊 统计

- 总共转换: **106** 处
- ✅ 低风险: 5 处 (简单字符串)
- ⚠️ 中风险: 92 处 (字符串拼接)
- 🔴 高风险: 9 处 (DOM 混合)

## 🔴 高风险项 (需人工复核)

### 1. src/settings/Settings.ts:107
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 2. src/settings/Settings.ts:167
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 3. src/settings/Settings.ts:193
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 4. src/settings/Settings.ts:350
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 5. src/settings/Settings.ts:502
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 6. src/settings/Settings.ts:635
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 7. src/settings/Settings.ts:710
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 8. src/settings/Settings.ts:802
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

### 9. src/settings/Settings.ts:854
**类型**: DOM 混合 + 占位符
**风险说明**: 使用 innerHTML 可能影响事件绑定

## ⚠️ 中风险项

共 92 处字符串拼接已自动合并，建议快速检查。

## ✅ 低风险项

共 5 处简单字符串已自动替换，无需复核。

---

> 生成时间: 2026-01-18T18:37:43.570Z
