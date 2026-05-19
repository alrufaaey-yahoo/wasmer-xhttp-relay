# wasmer-xhttp-relay

A high-performance XHTTP relay for Wasmer Edge, based on [InternetAzad/XHTTP](https://github.com/InternetAzad/XHTTP).

## Configuration

The relay is configured to forward requests to:
`TARGET_DOMAIN = https://thumbayan.com:443`

## Deployment

To deploy this relay to Wasmer Edge:

1. Install Wasmer CLI: `curl https://get.wasmer.io -sSfL | sh`
2. Login: `wasmer login`
3. Deploy: `wasmer deploy`

## Local Development

Run the relay locally using:
`wasmer run .`
