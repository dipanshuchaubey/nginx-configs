# Getting Started

To use these configurations, you will need to have Nginx installed on your server. If you haven't installed Nginx yet, you can do so by following the instructions in the [official Nginx documentation](https://nginx.org/en/docs/installation.html).

Once you have Nginx installed, you can clone this repository to your server using the following command:

```bash
git clone https://github.com/dipanshuchaubey/nginx-configs.git
```

## Using the Configurations

The configurations in this repository are organized by domain name. To use a configuration for a specific domain, you can copy the configuration file to the appropriate location on your server.

For example, let's say you want to use the configuration for the domain example.com. You would copy the file `example.com.conf` to the `/etc/nginx/conf.d/` directory:

```bash
sudo cp nginx-configs/example.com.conf /etc/nginx/conf.d/
```

After copying the file, you will need to restart Nginx for the changes to take effect:

```bash
sudo systemctl restart nginx
```

## Contributing

If you have improvements or suggestions for these configurations, please feel free to submit a pull request. We welcome contributions from the community.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
