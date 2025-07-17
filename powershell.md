# PowerShell

Search for all files containing API_KEY

    Get-ChildItem -Path C:\Users -Recurse -ErrorAction SilentlyContinue | Select-String “API_KEY”

