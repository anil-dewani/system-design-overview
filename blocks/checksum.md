# Checksum Overview

## Definition
- A checksum is a simple type of redundancy check that is used to detect errors in data.

## Usage in System Design
- **Data Integrity**: Ensures that data has not been altered, intentionally or unintentionally, during transmission or storage.
- **Error Detection**: Quickly identifies errors in data packets transmitted over unreliable networks.

## Calculation Methods
- **Parity Bits**: Adds a parity bit that makes the number of 1s even or odd.
- **Checksum Algorithms**: Includes simple sum checks, cyclic redundancy checks (CRC), and hash functions.

## Application Contexts
- Used in various networking protocols, file downloads, and software distribution to verify the integrity of data.

## Limitations
- Not foolproof; better for accidental errors than malicious tampering.

This markdown summary captures the concept of checksums within the context of system design, emphasizing their role in ensuring data integrity and error detection.
