# create-st-app

A command-line tool for creating new projects.

## Installation

To install the `create-solito-tRPC-app`, follow these steps:

1. Clone the repository from GitHub:

`git clone https://github.com/joegoggin/create-solito-tRPC-app.git`

2. Add the `create-ts-app` bash script to your `.bashrc` file in Linux:

`echo ‘export PATH=“$PATH:/path/to/create-solito-tRPC-app”’ >> ~/.bashrc source ~/.bashrc`

Make sure to replace `/path/to/create-solito-tRPC-app` with the actual path to the cloned repository on your system.

## Usage

`create-st-app`

## Options

- `-n <name>` : Specify the name of the app to create. This will also be the name of the project's root directory.

- `-p <path>` : (Optional) Specify the path to the directory where the project will be created. A directory with the specified project name will be created within this directory.

## Defaults

- `-p` : `~/Projects`

## Examples

1. `create-st-app -n your-project-name`
   This command will create a project located at `~/Projects/your-project-name`.

2. `create-st-app -n your-project-name -p /home/user/myDir`
   This command will create a project located at `/home/user/myDir/your-project-name`.

## License

[MIT](LICENSE)
