Run the following command to get the default admin password. Default username is admin

        kubectl -n devtroncd get secret devtron-secret -o jsonpath='{.data.ACD_PASSWORD}' | base64 -d

