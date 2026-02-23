# DRF Serializer API

A simple RESTful API project built with **Django REST Framework** to demonstrate CRUD operations, serializer usage, and API endpoint creation.

---

## 🚀 Features

* Create, Read, Update, and Delete (CRUD) operations for models
* **Serializer** classes to convert Django model instances to JSON and validate incoming data
* API endpoints implemented using **Django REST Framework views**
* Integration with **Django ORM** and PostgreSQL database
* Ready for expansion with authentication, filtering, and pagination

---

## 🛠 Technologies

* **Language:** Python 3.x
* **Framework:** Django, Django REST Framework
* **Database:** PostgreSQL (or SQLite for local testing)
* **Tools:** Git, GitHub, Postman (for API testing)

---

## 🔹 Installation

1. Clone the repository:

```bash
git clone https://github.com/mehroj-saparov-io/drf-serializer.git
```

2. Navigate to the project folder:

```bash
cd drf-serializer
```

3. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Apply migrations:

```bash
python manage.py migrate
```

6. Run the development server:

```bash
python manage.py runserver
```

---

## 🔹 API Endpoints

| Endpoint           | Method    | Description            |
| ------------------ | --------- | ---------------------- |
| `/api/items/`      | GET       | List all items         |
| `/api/items/`      | POST      | Create a new item      |
| `/api/items/<id>/` | GET       | Retrieve a single item |
| `/api/items/<id>/` | PUT/PATCH | Update an item         |
| `/api/items/<id>/` | DELETE    | Delete an item         |

*(Replace `items` with your model name)*

---

## 💡 Usage

* Use **Postman** or **curl** to interact with API endpoints
* Responses are in **JSON format**
* Extend the project with authentication, filtering, or pagination as needed

---

## 📂 Project Structure

```
drf-serializer/
│
├── api/
│   ├── models.py        # Django models
│   ├── serializers.py   # DRF serializers
│   ├── views.py         # API views
│   ├── urls.py          # API routes
│
├── drf_serializer/
│   ├── settings.py
│   └── urls.py
│
└── manage.py
```

---

## ⚡ Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

