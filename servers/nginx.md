# Basic NGINX Commands [:house:](../README.md)

#### Start Nginx

```console
sudo service nginx start
```

<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>


```console
sudo service nginx start
```

#### Stop Nginx

```console
sudo service nginx stop
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
sudo systemctl stop nginx
```
#### Restart Nginx

```console
sudo service nginx restart
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
sudo systemctl restart nginx
```

#### Reload Nginx with updated configuration

```console
sudo service nginx reload
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
sudo systemctl reload nginx
```

#### Verify Nginx configuration

```console
sudo nginx -t
```

#### Add new virtual host to Nginx

- Create a new virtual host file in - `/etc/nginx.sites-available/<virtual-host-filename>`
- Update this file with virtual host configuration.
- Create a symbolic link to this file in the `/etc/nginx-sites-enabled` directory.

    ```shell
    sudo ln -s /etc/nginx/sites-available/<virtual-host-filename> /etc/nginx/sites-enabled/<virtual-host-filename>
    ```

- Test configuration

    ```shell
    sudo nginx -t
    ```

- Restart Nginx to load configuration if test succeeds

    ```shell
    sudo systemctl restart nginx
    ```
