# Genego

Genego is a Django-based web application that integrates Ensembl's gene annotation data with Gene Ontology. It allows users to explore the functional annotations and relationships of specific genes or gene sets.

## Features

- Explore gene functional annotations: View detailed information about individual genes, including their annotations, associated Gene Ontology terms, and related data from Ensembl's gene annotation.
- Gene set analysis: Analyze gene sets to understand their functional enrichment and relationships using Gene Ontology terms.
- Interactive user interface: The web application provides a user-friendly interface to navigate and search for genes, gene sets, and functional annotations.
- Database integration: Genego integrates Ensembl's gene annotation data and Gene Ontology to provide comprehensive and up-to-date information for gene analysis.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/genego.git
```

2. Set up a virtual environment (optional but recommended):

```bash
python3 -m venv genego-env
source genego-env/bin/activate
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Perform database migrations:

```bash
python manage.py migrate
```

5. Load Ensembl gene annotation and Gene Ontology data:

```bash
python manage.py load_data
```

6. Start the development server:

```bash
python manage.py runserver
```

7. Access the application in your web browser at `http://localhost:8000/`.

## Usage

- **Gene Search**: Use the search functionality to find specific genes by name, Ensembl ID, or other identifiers. Click on a gene to view detailed information, including functional annotations and related Gene Ontology terms.

- **Gene Set Analysis**: Navigate to the gene sets section to analyze pre-defined or user-defined gene sets. Explore the functional enrichment of gene sets using Gene Ontology terms and examine relationships between different gene sets.

- **Browse Annotations**: Browse through the available functional annotations and Gene Ontology terms to gain insights into gene function and ontology.

## Contributing

Contributions are welcome! If you'd like to contribute to Genego, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive commit messages.
4. Push your changes to your fork.
5. Submit a pull request detailing your changes.

Please ensure that your code adheres to the project's coding conventions and includes appropriate tests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project utilizes data from Ensembl and Gene Ontology. Refer to their respective documentation and licenses for more information.
