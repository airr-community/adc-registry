# AIRR Data Commons Registry Governance

One of the goals of the AIRR Community is to promote the sharing of AIRR-seq data. One of the
key mechanisms for this sharing is the [AIRR Data Commons (ADC)](https://docs.airr-community.org/en/latest/adc/adc.html).
The ADC is a network of distributed repositories that adhere to the [AIRR Community data
standards](https://docs.airr-community.org/en/latest/standards/overview.html).

In order to facilitate the sharing of data across the ADC, it is necessary to be able to discover repositories
that adhere to the ADC standards. This document describes the governance for the AIRR Data Commons (ADC) Registry. 
The ADC Registry provides a mechanism to find and access the repositories in the ADC.
The document provides information about the processes used to manage and approve repositories that
are listed in the ADC Registry as well as the processes to monitor and determine reliability
of those repositories. The ADC Registry is maintained and managed by the [AIRR Community 
Common Repository Working Group](https://www.antibodysociety.org/the-airr-community/airr-working-groups/repository/).

## Guidelines for repositories in the ADC

Repositories must:
- Implement the [AIRR Data Commons Query API](https://docs.airr-community.org/en/latest/api/adc_api_overview.html) for querying the repository
- Be accessible from any IP number (no IP filtering other than security/DOS filtering)
- Pass the [ADC API query test suite](https://github.com/airr-community/adc-api-tests)
- Provide a data steward contact for the repository
- Have documented contact mechanisms for contacting the data steward for the repository
- Maintain a reasonable uptime
- Demonstrate ongoing ADC API compliance through passing the [ADC API query test suite](https://github.com/airr-community/adc-api-tests)

## Applying for registering a repository

The process for registering a repository is straightforward:

- Fill out the ADC Registry submission form to describe how your repository meets the ADC guidelines
- Send the submission form to common-repository@airr-community.org
- The submission will be reviewed by the Common Repository Working Group
- Iterative feedback will be provided and issues that need to be adressed will be identified
- Final submission will be reviewd by the Common Repository Working Group
- Approved repositories will be added to the ADC Registry

## Updating information about a repository in the ADC Registry

To change the details for a repository in the ADC Registry, please have the registered data steward contact the
Common Repository Working Group on common-repository@airr-community.org with the updated information.

## Removing a repository from the ADC Registry

To remove a repository from the ADC Registry, please have the registered data steward contact the
Common Repository Working Group on common-repository@airr-community.org and request removal of the
repository.

## Repository removal due to non-compliance

If a repository has been added to the registry but falls out of compliance with the ADC Guidelines above,
the Common Repository Working Group will assess the non-compliance, and if deemed appropriate will contact
the data steward for the repository. If the non-compliance can not be resolved, the repository will be
recommended for removal. A vote of the Common Repository Working Group will be held, and if the removal
recommendation is approved the repository will be removed from the ADC Registry.


