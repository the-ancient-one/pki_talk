# Cryptography in the Wild (Public Key Infrastructure, Certificates)
Talk/Session for warwick Msc Cyber Secuirty students.

## Description
A PKI (Public Key Infrastructure) is a system that enables the secure exchange of information over a network. One of the key components of a PKI is digital certificates.

Digital certificates are electronic documents that verify the authenticity of a party involved in a communication. They are issued by a trusted third party called a Certificate Authority (CA), in this instance we would be using Let's Encrypt's as CA. The certificate contains the public key of the party, along with other information such as the party's name, organization, and expiration date.

Digital certificates play a crucial role in various security protocols, such as SSL/TLS for secure web communication and S/MIME for secure email communication. They provide a mechanism for verifying the identity of parties involved in a communication and establishing a secure channel for data exchange.

## Repository File Structure
Here is the file structure of the repository:

| File/Folder | Description |
|-------------|-------------|
| README.md   | The main documentation file |
| docker-compose.yml    | The docker file for startn nginx proxy server |
| slides/       | Slides used in the presentation |
| LICENSE     | The license file |

Feel free to modify the file structure according to your project's needs.

## Repo Structure

```
.
├── LICENSE
├── README.md
├── docker-compose.yml
└── slides
    └── pki_talk_slides.pdf
```

## Nginx Proxy Server UI
The repository includes an Nginx Proxy Server UI that allows you to easily manage and configure your Nginx proxy server. This UI provides a user-friendly interface for managing server blocks, SSL certificates, and other Nginx configurations.

To access the Nginx Proxy Server UI, follow these steps:

1. Make sure you have Docker and Docker Compose installed on your system.
2. Open a terminal and navigate to the root directory of the repository.
3. Run the following command to start the Nginx Proxy Server UI:

    ```bash
    docker-compose up --force-recreate -d
    ```

    This command will build the necessary Docker images and start the containers in the background.
4. Once the containers are up and running, you can access the Nginx Proxy Server UI by opening a web browser and navigating to `http://localhost:81`.
5. From the UI, you can configure server blocks, SSL certificates, and other Nginx settings according to your project's needs.

Please note that the Nginx Proxy Server UI is just one component of the overall PKI system. It works in conjunction with the digital certificates and other components to provide secure communication over a network.

## License

Information about the license for your project.
