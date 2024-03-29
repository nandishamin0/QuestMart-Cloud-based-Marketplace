# QuestMart

QuestMart is a web application designed as a marketplace for buying and selling items, as well as facilitating item requests for items not currently available. Users can browse listed items, interact with sellers, and fulfill requests from other users.

## Features

- **Buying and Selling**: Users can list items for sale and browse items listed by other users.
- **Item Requests**: Users can submit requests for items they wish to buy, but which are not currently listed for sale.
- **Direct Communication**: Users can communicate directly with sellers to negotiate terms and arrange purchases.
- **Secure Authentication**: Secure user authentication ensures the safety of user accounts and transactions.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap, jQuery
- **Backend**: Python (Django framework)
- **Database**: MySQL (hosted on Google Cloud SQL)
- **Cloud Hosting**: Google Cloud Platform (GCP)
- **Load Balancing**: Google Cloud Load Balancing for optimal performance and DDoS protection.

## Deployment

QuestMart is deployed on Google Cloud Platform (GCP) using Google Application Engine, Google Cloud SQL for the database and Google Cloud Load Balancing for optimized performance and security against DDoS attacks.

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/nandishamin0/QuestMart-Cloud-based-Marketplace.git
```

2. Navigate to the cloned repository:

```bash
cd QuestMart-Cloud-based-Marketplace/questmart
```
   
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Set up Google Cloud SQL instance and configure database settings in Django settings file.

5. Run migrations to create database tables:

```bash
python manage.py migrate
```

6. Run the development server:

```bash
python manage.py runserver
```

7. Access the application in your web browser at `http://localhost:8000`.

## Contributing

Contributions to QuestMart are welcome! Please feel free to submit bug reports, feature requests, or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
