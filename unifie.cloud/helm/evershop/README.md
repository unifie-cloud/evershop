# EverShop helm chart

Evershop - https://evershop.io

## Globals variables

| Name                            | Description       |
| ------------------------------- | ----------------- |
| global.postgresql.auth.database | Database name     |
| global.postgresql.auth.username | Database username |
| global.postgresql.auth.password | Database password |
| global.postgresql.auth.port     | Database port     |
| global.postgresql.auth.host     | Database host     |

## variables

| Name           | Description                                |
| -------------- | ------------------------------------------ |
| evershop.image | Image (default `evershop/evershop:latest`) |

## Tip

Add extension [Amazon S3 Storage](https://evershop.io/extensions) or [Azure Blob Storage](https://evershop.io/extensions) for storing media files separately from deployment.
It will allow to use stateless deployment instead of Stateful.
