![image](https://user-images.githubusercontent.com/6322484/186876085-f489ec52-b9ec-402e-bf49-8895784ff833.png)

# Pehelypress

>pehely (Hungarian, n): (down) feather

I just wanted to install [Wodpress](https://wordpress.org) on my [k3s](https://k3s.io) instance. This Helm chart exists to make that simple.

## Installation

However you usually install Helm charts. [I personally use](https://github.com/valerauko/sut/tree/master) [ArgoCD](https://argoproj.github.io/argo-cd/) to manage that stuff.

## Values

Please refer to [values.yaml](https://github.com/valerauko/pehelypress/blob/master/values.yaml).

## Reason

Bitnami's [Wordpress chart](https://github.com/bitnami/charts/tree/master/bitnami/wordpress) while probably wonderful runs some apparently pretty heavy installation scripts that ate up all the resources on my tiny server and kept failing.

This chart does nothing so fancy and uses the official [Wordpress](https://hub.docker.com/_/wordpress/) and [Nginx](https://hub.docker.com/_/nginx/) images.

Thus the name: featherweight.

## Credit

Cover photo by <a href="https://unsplash.com/@evieshaffer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Evie S.</a> on <a href="https://unsplash.com/s/photos/feather?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>.
