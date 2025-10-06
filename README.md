# BudgetWise: Expense and Budget Manager

## Concept summary

 Our project involves the development of an Expense Tracking and Budgeting Application aimed at enhancing users' financial management practices. Through this platform, users can efficiently manage their expenses, create personalized budgets, and optimize their spending habits. The application will offer intuitive data visualization tools for tracking spending patterns, with real-time alerts that will notify users of budget breaches, ensuring fiscal discipline.

## Prerequisites

### For Demo

- Terraform

### For Development

- Node v21.6.1
- npm v10.2.4
- Terraform v1.5.7
- AWS Credentials
- Docker Desktop v4.22.1
- Docker CLI v24.0.5
- Docker Hub Credentials

## How to deploy it

1. Naviagte to the terrform template folder

```
cd tf-templates
```

2. Update your AWS credentials in `provider.tf`
3. Run the following terraform commands:

```
terraform init
```

```
terraform plan
```

```
terraform apply
```

4. For clean-up, run:

```
terraform destroy
```

## License

MIT License. See LICENSE for details.
