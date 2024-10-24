# Swagger Basic

create openapio.yaml
```yaml
openapi: "3.0.0"

info:
  title: "Sample API"
  version: 1.0.0

paths:
  "/message":
    get:
      summary: "Smaple API operation"
      description: "Sample API get opration"
      responses:
        "200":
          description: "Success operation"
          content:
            application/json: # JSON形式
              schema: # 中身が
                type: string
                example: "Hello World !"
```

Shift + Alt + P

Swagger Editorが起動する。