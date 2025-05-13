# 내가 Zod를 사랑할 수 밖에 없는 N가지 이유

## 1. parse is better than validate

```typescript
const schema = z.object({
  name: z.string(),
  age: z.coerce.number(),
})
```

## 2. 
