# ES, Kibana, Filebeat & Azure storage account

Plug and play to analyze files in a Azure storage account

1. Change `filebeat/filebeat.yml` with correct credentials, or change the to the `input` to what you need.
2. `cd repo-folder`
3. `docker compose up`
4. ⌛ *wait a good minute*
5. http://localhost:5601
6. Once inside Kibana, add a new dataview that matches `logs` index. (Menu -> Management | Stack Management -> Kibana | Data Views)