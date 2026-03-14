# Product CRUD API (FastAPI + SQLite)

## 1. Install dependencies

```bash
pip install -r requirements.txt
```

## 2. Start service

```bash
uvicorn main:app --reload
```

## 3. API docs

Open:

- http://127.0.0.1:8000/docs
- http://127.0.0.1:8000/redoc

## 4. Endpoints

- `POST /products` Create product
- `GET /products` List products
- `GET /products/{product_id}` Get product detail
- `PUT /products/{product_id}` Update product
- `DELETE /products/{product_id}` Delete product

## 5. Example payload

```json
{
  "name": "iPhone 16",
  "description": "256GB",
  "price": 7999.0,
  "stock": 20
}
```
