# 減少 unnecessary re-rendering
*大多數 re-rendering 是微不足道的，它們甚至不值得開發者花時間優化。*

減少 unnecessary render 可以簡單分為三種作法:
- 不使用 `React.memo()`
- 單獨使用 `React.memo()`
- 使用 `React.memo()` 搭配 `useCallback` / `useMemo`

## 不使用 `React.memo()`
Dan 在他的 blog *[Before You memo()](https://overreacted.io/before-you-memo/)* 提出了兩種優化 re-render 的基本技巧。它們出乎意料的基本，建議先閱讀此文章。

## 單獨使用 `React.memo()`
未完..
## 使用 `React.memo()` 搭配 `useCallback` / `useMemo`
未完..
