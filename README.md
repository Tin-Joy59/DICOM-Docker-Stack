# DICOM-Docker-Stack
A DICOM Docker stack with ORTHANC Server, MariaDB database and MedDream frontend viewer.

The credentials for MedDream are `user`:`password`

`/data` is the ingest directory for the ORTHANC server. It's set to read-only. Once the files are placed in it, the ORTHANC Indexer add-on should pick them up automatically, analyse them and display them in MedDream's UI.
