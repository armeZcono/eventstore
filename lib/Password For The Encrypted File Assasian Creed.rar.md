
 
# How to Unlock RAR/WinRAR Password for the Encrypted File Assasian Creed.rar
 
If you have downloaded the encrypted file assasian creed.rar from some sources, you may need to enter a password to extract it. But what if you don't know or forget the password? Don't worry, there are some ways to unlock RAR/WinRAR password for such files. In this article, we will show you three methods to do that.
 
**Download — [https://kneedacexbrew.blogspot.com/?d=2uJyZY](https://kneedacexbrew.blogspot.com/?d=2uJyZY)**


 
## Method 1: Use Frequently-Used Passwords
 
The simplest way to unlock RAR/WinRAR password is to try some common passwords that you usually use. For example, you can try your birthday, your name, your phone number, your email address, etc. You can also try some default numbers like 123456, 00000, 007, etc. If you are lucky enough, you may find the right password and open the file.
 
## Method 2: Use Notepad and Commands
 
This is a more complicated way to unlock RAR/WinRAR password, but it may work for some cases. You need to create a Notepad file and paste some specific commands to it. Then save it as a bat file and run it. It will try to find the password of the RAR file by using a brute-force attack. Here are the steps:
 
1. Create a Notepad file and copy and paste the following commands to it:


        REM ============================================================
        @echo off
        title Rar Password Cracker
        mode con: cols=47 lines=20
        copy "C:\Program Files\WinRAR\Unrar.exe"
        SET PSWD=0
        SET DEST=%TEMP%\%RANDOM%
        MD %DEST%
        :RAR
        cls
        echo ----------------------------------------------
        echo GET DETAIL
        echo ----------------------------------------------
        echo.
        SET/P "NAME=Enter File Name : "
        IF "%NAME%"=="" goto NERROR
        goto GPATH
        :NERROR
        echo ----------------------------------------------
        echo ERROR
        echo ----------------------------------------------
        echo Sorry you can't leave it blank.
        pause
        goto RAR
        :GPATH
        SET/P "PATH=Enter Full Path : "
        IF "%PATH%"=="" goto PERROR
        goto NEXT
        :PERROR
        echo ----------------------------------------------
        echo ERROR
        echo ----------------------------------------------
        echo Sorry you can't leave it blank.
        pause
        goto RAR
        :NEXT
        IF EXIST "%PATH%\%NAME%" GOTO START
        goto PATH
        :PATH
        cls
        echo ----------------------------------------------
        echo ERROR
        echo ----------------------------------------------
        echo Opppss File does not Exist..
        pause
        goto RAR
        :START
        SET /A PSWD=%PSWD%+1
        echo 0 1 0 1 1 0 0 1 0 0 1 0 0 1 0 1 0 0 1 0 > %DEST%\Matrix.tmp
        FOR /F "tokens=1-5 delims= " %%A IN (%DEST%\Matrix.tmp) DO SET M1=%%A& SET M2=%%B& SET M3=%%C& SET M4=%%D& SET M5=%%E 
        del %DEST%\Matrix.tmp >nul 
        SET MATRIX=%M1%%M2%%M3%%M4%%M5%
        if %MATRIX% EQU 00000000000000000000 goto CRACKED 
        title Cracking Password... %PSWD%
        cls 
        echo.
        echo     ====================== CRACKING ======================
        echo.
        echo                   [-*-*-*-*-*-*-*-*-*-*-*-]
        echo                   [-*-*-*-*-*-*-*-*-*-*-*-]
        echo                   [-*-*-*-*-*-*-*-*-*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        echo                   [-*-*-*-Cracking...*-*-*-]
        Un 8cf37b1e13

        
