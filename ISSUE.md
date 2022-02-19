# Issue
On recent releases of HA, I am facing an issue with the display of the gauge, using the default light or dark theme.

Dark theme:

![2022-02-19_094807](https://user-images.githubusercontent.com/58231487/154793886-12c5b1aa-4469-4a7c-9bb7-d7def5421959.png)

Light theme:

![2022-02-19_094830](https://user-images.githubusercontent.com/58231487/154793899-4fa37a60-bcf1-47cd-861e-22c0c1a4bb8a.png)


With the style inspector of the browser, the variable `--paper-card-background-color` is not set in `.gauge-b`. Replacing this variable with `--card-background-color` fix the issue.

![2022-02-19_101802](https://user-images.githubusercontent.com/58231487/154794766-c07842f9-9bde-4db3-869b-e15151171cb9.png)


After:

![2022-02-19_101859](https://user-images.githubusercontent.com/58231487/154794849-2f92f890-6f1f-4424-ab05-74d4d5b4f26e.png)
![2022-02-19_101914](https://user-images.githubusercontent.com/58231487/154794851-75ca8ade-fa21-43d7-a59c-06abe5c18f3b.png)

![2022-02-19_102007](https://user-images.githubusercontent.com/58231487/154794852-9e99d0f7-b324-48b7-959a-e55e7eaae87e.png)
