File Integrity Monitoring PowerShell Script

Write-Host ""
Write-Host "What would you like to do?"
Write-Host "A) Collect new Baseline?"
Write-Host "B) Begin monitoring files with saved Baseline?"
Write-Host ""

$response = Read-Host -Prompt "Please enter 'A' or 'B'"
Write-Host ""
