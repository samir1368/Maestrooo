# Maestro test suite

`test.yaml` is the single suite entry point. It starts from a cleared app state, completes login, and then runs the feature flows.

Set the variables listed in `.env.example` in your CI secret store or shell before running the suite. They deliberately have no committed values because they contain environment-specific test data and may be sensitive.

Run the suite from this directory:

```powershell
maestro test .
```
# کارتها باید شاپرکی شده باشند
# کارت مبدا و مقصد رو باید تو لیست هاتون داشته باشید
# شروع تست از کلاس test.yaml است
