# birch-desk-etl

Attendance tracking service for campus front offices.

## Development

```sh
terraform init && terraform plan
```

Run the tests with `terraform validate`.

## Configuration

Settings come from environment variables. Copy `.env.example` to `.env` for local development and never commit real credentials.
