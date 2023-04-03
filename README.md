# Demonstrate Nx + Angular + Storybook 7

Steps:

1. `npx create-nx-workspace@latest my-wksp --preset=apps`
2. `cd my-wksp`
3. `npm i --save-dev @nrwl/storybook@latest @nrwl/angular@latest`
4. `npx nx g @nrwl/angular:application front-desktop`
5. `npx nx g @nrwl/storybook:configuration front-desktop --storybook7Configuration --storybook7UiFramework=@storybook/angular`
6. `npm i --save-dev react react-dom`
7. `npx nx build-storybook front-desktop`

Storybook builds successfully.