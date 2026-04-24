# បូត SMOS GANG Welcome

បូត Discord សម្រាប់សារស្វាគមន៍ សារចាកចេញ និងការគ្រប់គ្រងតួនាទីស្វ័យប្រវត្តិ ជាមួយភាសាខ្មែរ។

## មុខងារ

- 🎉 សារស្វាគមន៍ផ្ទាល់ខ្លួន
- 👋 សារចាកចេញ
- 📩 សារ DM ស្វាគមន៍/ចាកចេញ
- 🎭 ការផ្តល់តួនាទីស្វ័យប្រវត្តិ
- 📝 បញ្ជាក់ Slash
- 👤 ប្រព័ន្ធ Admin Bypass

## អថេរ

| អថេរ                  | បរិយាយ                                  |
| --------------------- | --------------------------------------- |
| `TOKEN`               | Token បូត Discord របស់អ្នក              |
| `CLIENT_ID`           | Client ID បូត Discord របស់អ្នក          |
| `ADMIN_IDS`           | លេខ ID អ្នកប្រើប្រាស់ ដាក់ដោយក្បៀស      |
| `COMMAND_LOG_WEBHOOK` | URL Webhook Discord សម្រាប់កត់ត្រាបញ្ជា |

## អថេរសម្រាប់សារ

- `{user}` - លើកឡើងអ្នកប្រើប្រាស់
- `{user.username}` - ឈ្មោះអ្នកប្រើប្រាស់
- `{user.id}` - ID អ្នកប្រើប្រាស់
- `{user.avatar}` - URL Avatar អ្នកប្រើប្រាស់
- `{user.createdAt}` - កាលបរិច្ឆេទបង្កើត (DD/MM/YY)
- `{user.createdAtFull}` - កាលបរិច្ឆេទពេញ
- `{server}` - ឈ្មោះម៉ាស៊ីនបម្រើ (ខ្លី)
- `{server.name}` - ឈ្មោះម៉ាស៊ីនបម្រើ
- `{server.id}` - ID ម៉ាស៊ីនបម្រើ
- `{server.icon}` - URL Icon ម៉ាស៊ីនបម្រើ
- `{membercount}` - ចំនួនសមាជិក
- `{membercount.ordinal}` - ចំនួនសមាជិក (ជាមួយ ordinal)
- `{#channel}` - លើកឡើងឆានែលតាមឈ្មោះ
- `{@role}` - លើកឡើងតួនាទីតាមឈ្មោះ

## បញ្ជា

- `/autorole` - គ្រប់គ្រងតួនាទីស្វ័យប្រវត្តិ (set, remove, view)
- `/setup` - កំណត់ប្រព័ន្ធស្វាគមន៍/ចាកចេញ
- `/info` - បង្ហាញព័ត៌មានការកំណត់បច្ចុប្បន្ន
- `/help` - បង្ហាញវិធីប្រើប្រាស់

## របៀបដំឡើង

1. ដំឡើង dependencies:

```bash
npm install
```

2. ចម្លង `.env.example` ទៅ `.env` និងបំពេញព័ត៌មាន:

```bash
cp .env.example .env
```

3. ចាប់ផ្តើមបូត:

```bash
npm start
```

## អាជ្ញាប័ណ្ណ

MIT
npm start

```

## License

MIT
```
