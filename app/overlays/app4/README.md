## General
- This project just for testing :
    - Secret mounted on pod volume
    - Secret mounted on pod env variable
    - All secret source from external Vault with ESO
    - All secret will be print on web based php (configmap & secret env var differentiation)
    - If you want to try, make sure you have :
        - Vault with path : `secret/an-web/message`
        - name of secret `message-from-vault` with key `message`
