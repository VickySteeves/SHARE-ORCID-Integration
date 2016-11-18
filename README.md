# SHARE-ORCID-Integration

Populating SHARE dataset with ORCID data. Meeting notes and materials found here: https://osf.io/n9wft/

## Relevant Links
A link to the Python wrapper for the ORCID sandbox API: https://github.com/ORCID/python-orcid

To run any of the ORCID APIs you’ll need credentials and ultimately an OAuth2 token:  
http://support.orcid.org/knowledgebase/articles/116739-register-a-member-api-client-application
http://support.orcid.org/knowledgebase/articles/343182-register-a-public-api-client-application

## ORCID Wrapper Jupyter Notebook Instructions
This Python wrapper for the ORCID Public API v1.2 has been developed for the SHARE Curation Associates group working to integrate selected ORCID data into SHARE Notify.  It presupposes that Python 3, Jupyter Notebook, Requests and JSON dependencies have been met.

Understand that only ORCID profiles in the public (production) server with visibility set to "public" can be captured by these queries.

I recommend that you create a virtual Python environment with Virtualenv or Conda, once you have cloned this simple Jupyter Notebook. Take care of the dependencies by running "pip install -r requirements.txt"  Once that is done, launch Jupyter Notebook, open orcid-wrapper.ipynb, and begin experimenting. 

The ORCID Public API does not require authentication for read-only access. 
