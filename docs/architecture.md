# Architecture and Encoding Pipeline

## Data Flow
1. Field serialization according to ZATCA specification.
2. UTF-8 byte conversion with length byte prefix.
3. Concatenation and Base64 wrapping.
4. Rendering to bitmap QR Code image.