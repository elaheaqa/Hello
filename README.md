@echo off
REM Simple script to update GitHub repository on Windows
REM Usage: update.bat "your commit message"

:: Step 1: Add all changes
git add .

:: Step 2: Commit with message
IF "%~1"=="" (
    git commit -m "Update repository"
) ELSE (
    git commit -m "%~1"
)

:: Step 3: Push to GitHub
git push origin main














session
closet
good job
government
brave

