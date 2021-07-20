# Devcontainer for React-Native under Expo

This devcontainer was created to develop on react-native applications
using Expo.

Everything in this devcontainer can be modified. It is just a **basic template**.

## Using within your project

If you want to use this devcontainer template for your projects,
you just have to clone the repository in the root of your project.

Inside `.devcontainer/devcontainer.json`, you can add all the extension you
wish to see in your workspace.

To add new node packages or OS packages, you can directly edit the
`Dockerfile` in `.devcontainer/`.

## Versions

The expo container is configured to run on `node 0.16-buster` but you can
easily change this by modifing the `VARIANT` build arg in
`.devcontainer/devcontainer.json`.
