# update_thepython
versiyani tekshirish uchun: python -V yoki python --version



1-usul: Updater exe bilan.

1-step: https://www.python.org/downloads/




2-usul: PowerShell yoki cmd orqali

1-step: Windows+X va o'sha yerdan PowerShell(admin) ni bos

2-step: Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))


3-step: choco upgrade python -y


tamom
