# Power Hacks: Next-Gen Social Platform for University Communication

## Introduction

Power Hacks is a revolutionary communication platform designed to foster inclusivity, accessibility, and meaningful connections among university communities. Inspired by the need to disrupt traditional dialogue and combat negativity and misinformation, our platform aims to bridge divides and promote a future of positive communication. Launched in celebration of World Telecommunication Day (May 17th), Power Hacks empowers users to "disrupt the conversation" by providing a space for sharing ideas and engaging in constructive dialogues.

## Features

- **User-Friendly Interface**: Designed with simplicity and ease of use in mind, our platform caters to users of all ages and tech-savviness levels.
- **Accessibility**: Ensures that everyone, regardless of their abilities, can participate in conversations and share ideas freely.
- **Inclusivity**: Promotes a safe and welcoming environment where all voices are heard and respected.
- **Topic-Based Discussions**: Allows users to engage in focused conversations around various topics, facilitating knowledge exchange and idea generation.

## Technology Stack

- **Backend**: Django Framework
- **Database**: PostgreSQL
- **Frontend**: React.js
- **Authentication**: JWT Tokens
- **Deployment**: Docker & Kubernetes

## Getting Started

### Prerequisites

Ensure you have Python installed on your system. We recommend using Python 3.8 or newer.

### Installation

1. Clone the repository

    git clone https://github.com/Roro1839/Power_Hackthon01.git cd power-hacks

2. Create a virtual environment and activate it:

python -m venv env source env/bin/activate # On Windows use .\env\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt

4. Configure your database settings in `settings.py`.

5. Apply migrations:

    python manage.py migrate

6. Collect static files:

    python manage.py collectstatic


7. Run the server:


Your application should now be running at http://localhost:8000.

## Contributing

Contributions are welcome Please feel free to submit pull requests or report issues.

## License

MIT License

Copyright (c) 2024 Ronaldo Cheruiyot, Odour Kapisi, Kelvin Mwandiki, Felix Yator, Newton 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the conditions stated in the MIT License.
