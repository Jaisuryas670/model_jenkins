# Jenkins Git Checkout Lab

## Aim
To configure a Jenkins Freestyle project to retrieve source code from a GitHub repository and verify the checkout process.

## Tools Used
- Jenkins
- Git and GitHub
- WSL Ubuntu

## Procedure
1. Create a GitHub repository.
2. Create a Jenkins Freestyle project named `Git-CheckoutLab`.
3. Configure the Git repository URL in Source Code Management.
4. Add a shell build step to print a confirmation message.
5. Run the Jenkins job and verify the Console Output.

## Build Command
```bash
echo "Git repository checked"
```

## Expected Output
```text
Git repository checked
Finished: SUCCESS
```

## Result
Successfully configured a Jenkins Freestyle project to check out source code from GitHub and display a confirmation message in the console output.
