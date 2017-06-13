![Sails from scratch](https://guides.nanobox.io/assets/quickstart-icons/sails.png)

# Sails from scratch

Run a Sails app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-sails.git

# cd into the sails app
cd nanobox-sails
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local sails.dev

# Run sails as you would normally, with Nanobox
nanobox run sails lift
```

## Check it out

Visit your app at <a href="http://sails.dev:1337" target="\_blank">sails.dev:1337</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# your packages are available,
yarn list

# and your code is mounted
ls
```

## Now What?
For more details about running sails apps with nanobox visit [guides.nanobox.io/nodejs/sails/](https://guides.nanobox.io/nodejs/sails/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
