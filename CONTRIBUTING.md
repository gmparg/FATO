# Table Of Contents

- [Table Of Contents](#table-of-contents)
  - [Contributing to Food Allergen Traceability Ontology (FATO)](#contributing-to-food-allergen-traceability-ontology-fato)
  - [Code of Conduct](#code-of-conduct)
  - [Guidelines for Contributions and Requests](#guidelines-for-contributions-and-requests)
    - [Reporting problems with the ontology](#reporting-problems-with-the-ontology)
    - [Requesting new terms](#requesting-new-terms)
      - [Who can request a term?](#who-can-request-a-term)
      - [How to write a new term request](#how-to-write-a-new-term-request)
    - [How to add a new term](#how-to-add-a-new-term)
  - [Best Practices](#best-practices)
    - [How to write great issues?](#how-to-write-great-issues)
    - [How to create a great pull/merge request?](#how-to-create-a-great-pullmerge-request)
  - [RO mailing list](#ro-mailing-list)
  - [RO working group meetings](#ro-working-group-meetings)

## Contributing to Food Allergen Traceability Ontology (FATO)

First of all: Thank you for taking the time to contribute!

The following is a set of guidelines for contributing to FATO. 
These guidelines are not strict rules. Use your best judgment, and feel free to propose 
changes to this document in a pull request.

## Code of Conduct

The FATO team strives to create a welcoming environment for editors, users and other contributors.
Please carefully read our [Code of Conduct](CODE_OF_CONDUCT.md).

## Guidelines for Contributions and Requests


### Reporting problems with the ontology

Please use our [Issue Tracker](https://github.com/gmparg/FATO/issues) for reporting problems with the ontology. 


### Requesting new terms

Before you write a new request, please consider the following: 

- **Does the term already exist?** Before submitting suggestions for new ontology terms, check whether the term exist, 
either as a primary term or a synonym term. 
- **Can you provide a definition for the term?** It should be very clear what the term means, and you should be
able to provide a concise definition, ideally with a scientific reference.
- **Is the ontology in scope for the term?** Sometimes, it is hard to tell whether a term "belongs" in
and ontology. A rule of thumb is "if a similar term already exists, the new term is probably in scope."
It can be very helpful to mention a very similar concept as part of the term request!

#### Who can request a term?

Anyone can request new terms. However, there is not guarantee that your term will be added automatically. Since this is a 
community resource, it is often necessary to do at least some of the work of adding the term yourself, see below.

#### How to write a new term request

Request a new term _via_ the GitHub [Issue Tracker](https://github.com/gmparg/FATO/issues).

It is important to remember that it takes a lot of time for curators to process issues submitted to the tracker.
To make this work easier, please always use issue templates if they are available (https://github.com/oborel/obo-relations/issues/new/choose).

### How to add a new term

If you have never edited this ontology before, first follow a [general tutorial](https://oboacademy.github.io/obook/lesson/contributing-to-obo-ontologies)

**Process**:

1. Clone the repository (In case you are not an offical team member, create a fork first)
1. Create new branch in git, for example `git checkout -b issue123`
1. Open FATO.owl in your favourite editor, i.e. [Protege](https://protege.stanford.edu/). 
1. Perform your edit and save your changes
1. Commit changes to branch
1. Push changes upstream
1. Create pull request

## Best Practices


### How to write great issues?

1. **Write a detailed request:** Please be specific and include as many details as necessary, providing background information, and if possible, suggesting a solution. GOC editors will be better equipped to address your suggestions if you offer details regarding *'what is wrong'*, *'why'*, and *'how to fix it'*.

2. **Provide examples and references:** Please include any applicable references (such as PMIDs) for new term requests, and include also screenshots, or URLs illustrating the current ontology structure for other types of requests. 

3. **For new term request:** Be sure to provide suggestions for label (name), definition, references, position in hierarchy, etc.

4. **For updates to relationships:** Provide details of the current axioms, why you think they are wrong or not sufficient, and what exactly should be added or removed.

Creating a new issue in the tracker allows the RO editors and community to discuss proposed changes, fixes, or additions. 

Please refer to the [OBO Academy best practices](https://oboacademy.github.io/obook/lesson/term-request/).

### How to create a great pull/merge request?

Please refer to the [OBO Academy best practices](https://oboacademy.github.io/obook/howto/github-create-pull-request/)

## Guidelines for creating Pull Requests

Anyone is welcome to make Pull Requests (PRs), however, you are advised to coordinate with other FATO developers and announce your
intentions on the relevant GitHub issue first to avoid doing work that may later be rejected.
