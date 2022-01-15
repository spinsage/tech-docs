# Basic PM2 Commands [:house:](../README.md)

### Non Cluster Mode

#### Start an application with PM2

```console
pm2 start <app>.js --name <app-name-given-to-pm2>
```

#### Stop an application managed by PM2

```console
pm2 stop <app>.js
```

<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>


```console
pm2 stop <app-name-given-to-pm2>
```

#### Restart an application managed by PM2

```console
pm2 restart <app>.js
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
pm2 restart <app-name-given-to-pm2>
```

#### Reload an application managed by PM2

```console
pm2 reload <app>.js
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
pm2 reload <app-name-given-to-pm2>
```

#### Delete an application managed by PM2

```console
pm2 delete <app>.js
```
<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
pm2 delete <app-name-given-to-pm2>
```

#### List applications managed by PM2

```console
pm2 ls 
```

<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
pm2 list
```

<img align="left" alt="Spinsage Tech Docs" src="https://img.shields.io/badge/-OR-4267B2?style=for-the-badge&logoColor=white" /><br/>

```console
pm2 status
```

#### View PM2 Terminal Dashboard

```console
pm2 monit
```

### PM2 Clusters

#### Start an application with PM2 with multiple worker processes

```console
pm2 start <app>.js -i <max-worker-process-count>
```

#### Scale up the number of workers for an application managed by PM2

```console
pm2 scale <app>.js +<number-of-worker-process-count>
```

#### Scale up or down the number workers for an application managed by PM2

```console
pm2 scale <app>.js <number-of-worker-process-count>
```
