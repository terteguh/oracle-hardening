
2 Oracle Parameter Settings 
2.1 Listener Settings
2.1.1 Ensure 'extproc' Is Not Present in 'listener.ora' (Automated)
2.1.2 Ensure 'ADMIN_RESTRICTIONS_' Is Set to 'ON' (Automated) 
2.2 Database Settings
2.2.1 Ensure 'AUDIT_SYS_OPERATIONS' Is Set to 'TRUE' (Automated) 
2.2.2 Ensure 'AUDIT_TRAIL' Is Set to 'DB', 'XML', 'OS', 'DB,EXTENDED', or 'XML,EXTENDED' (Automated) 
2.2.3 Ensure 'GLOBAL_NAMES' Is Set to 'TRUE' (Automated) 
2.2.4 Ensure 'OS_ROLES' Is Set to 'FALSE' (Automated)
2.2.5 Ensure 'REMOTE_LISTENER' Is Empty (Automated)
2.2.6 Ensure 'REMOTE_LOGIN_PASSWORDFILE' Is Set to 'NONE' (Automated)
2.2.7 Ensure 'REMOTE_OS_AUTHENT' Is Set to 'FALSE' (Automated) 
2.2.8 Ensure 'REMOTE_OS_ROLES' Is Set to 'FALSE' (Automated) 
2.2.9 Ensure 'SEC_CASE_SENSITIVE_LOGON' Is Set to 'TRUE' (Automated) 
2.2.10 Ensure 'SEC_MAX_FAILED_LOGIN_ATTEMPTS' Is '3' or Less (Automated) 
2.2.11 Ensure 'SEC_PROTOCOL_ERROR_FURTHER_ACTION' Is Set to '(DROP,3)' (Automated)
2.2.12 Ensure 'SEC_PROTOCOL_ERROR_TRACE_ACTION' Is Set to 'LOG' (Automated) 
2.2.13 Ensure 'SEC_RETURN_SERVER_RELEASE_BANNER' Is Set to 'FALSE' (Automated)
2.2.14 Ensure 'SQL92_SECURITY' Is Set to 'TRUE' (Automated) 
2.2.15 Ensure '_trace_files_public' Is Set to 'FALSE' (Automated) 
2.2.16 Ensure 'RESOURCE_LIMIT' Is Set to 'TRUE' (Automated) 
2.2.17 Ensure 'PDB_OS_CREDENTIAL' is NOT null (Automated) 
2.3 SQLNET.ORA Settings 
2.3.1 Ensure 'ENCRYPTION_SERVER' Is Set to 'REQUIRED' (Automated) (Automated) 
2.3.2 Ensure 'SQLNET.CRYPTO_CHECKSUM_SERVER' Is Set to 'REQUIRED' (Automated) (Automated)
