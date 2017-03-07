# Virtualenv-Activator
A bash script for choosing and activating virtualenv.

#### How to use
   - Modify the script to match the virtualenv directory
   - Put the `.env` file in the directory containing the virtualenv.
   - Run the script by calling `sh .env`
   
##### Note
An easy way to automatically calling the script after using the `cd` command is to install [autoenv](https://github.com/kennethreitz/autoenv) using:

```
git clone git://github.com/kennethreitz/autoenv.git ~/.autoenv
echo 'source ~/.autoenv/activate.sh' >> ~/.bashrc
```
