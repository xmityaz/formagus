```typescript
interface FieldMeta {
  errors: any | null;
  isDirty: boolean;
  isTouched: boolean;
  isActive: boolean;
  isValidating: boolean;
  isRegistered: boolean;
  custom: {[key: string]: any};
  form: FormMeta;
}
```

- [FormMeta](/types/FormMeta)
