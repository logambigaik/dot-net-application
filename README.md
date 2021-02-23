# dot-net-application

# Installation
    sudo yum update 
    sudo rpm -Uvh https://packages.microsoft.com/config/centos/7/packages-microsoft-prod.rpm
    sudo yum install dotnet-sdk-5.0

# Check everything installed correctly
    dotnet

# Create dotnet App:
    dotnet new console -o myApp
    
# Open the app:
    cd myApp
# Open the program Program.cs

        using System;

        namespace myApp
        {
            class Program
            {
                static void Main(string[] args)
                {
                    Console.WriteLine("Hello World!");
                }
            }
        }
~

# Run your app
    dotnet run
# Check output 
    
 ![image](https://user-images.githubusercontent.com/54719289/108875162-e3569500-7622-11eb-934b-1501b5661cb5.png)
 
 
 
# For WebApplication:

        dotnet new webApp -o myWebApp --no-https
        cd myWebApp
        dotnet watch run




![image](https://user-images.githubusercontent.com/54719289/108886161-a4c6d780-762e-11eb-8e09-b951f8807538.png)




# [root@ip-172-31-24-194 opt]# dotnet new mvc
    The template "ASP.NET Core Web App (Model-View-Controller)" was created successfully.
    This template contains technologies from parties other than Microsoft, see https://aka.ms/aspnetcore/5.0-third-party-notices for details.

    Processing post-creation actions...
    Running 'dotnet restore' on /opt/opt.csproj...
    Determining projects to restore...
    Restored /opt/opt.csproj (in 93 ms).
    Restore succeeded.

# [root@ip-172-31-24-194 opt]# dotnet new webapp --force
    The template "ASP.NET Core Web App" was created successfully.
    This template contains technologies from parties other than Microsoft, see https://aka.ms/aspnetcore/5.0-third-party-notices for details.

    Processing post-creation actions...
    Running 'dotnet restore' on /opt/opt.csproj...
    Determining projects to restore...
    All projects are up-to-date for restore.
    Restore succeeded.

# Comment out https in Startup.cs:

![image](https://user-images.githubusercontent.com/54719289/108901169-8e297c00-7640-11eb-96e5-341ac1039aa7.png)


# Run the application with below command:

            dotnet run --urls "http://0.0.0.0:5000"

![image](https://user-images.githubusercontent.com/54719289/108907362-00ea2580-7648-11eb-80b6-e6d0e1e5a16c.png)

