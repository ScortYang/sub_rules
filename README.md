# sub_rules
clash rules based on ACL4SSR

## GitHub Action

This repository can be used as a GitHub Action with ZeroSSL certificate support.

### Inputs

- `email-address` (required): Email address for ZeroSSL registration credentials

### Example Usage

```yaml
- name: Use Sub Rules with ZeroSSL
  uses: ScortYang/sub_rules@main
  with:
    email-address: 'your-email@example.com'
```
