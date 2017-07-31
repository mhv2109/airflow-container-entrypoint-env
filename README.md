Workaround for adding environment variables in the entrypoint of [this image](https://github.com/puckel/docker-airflow/tree/1.8.1) when deploying container images using [Ansible Container](https://github.com/ansible/ansible-container) project.

Add environment file template and set {{ ENVIRONMENT_FILE_TEMPLATE }} to the path to that template.
