# Cryptography-Cipher
A Cryptography Cipher is a tool that transforms readable text (plaintext) into an unreadable format (ciphertext) using a specific algorithm and key. Building one introduces the core pillars of security: confidentiality and integrity.

What is it?
	A cipher is a mathematical formula for hiding information. Beginners usually start with:
	Substitution Ciphers: Swapping letters (e.g., the Caesar Cipher).
	Transposition Ciphers: Scrambling the order of characters.
	Symmetric Encryption: Using one secret key to both lock and unlock data.

The Basic Workflow
	Input: The user provides a message and a secret "key."
	Transformation: The script loops through the message, applying a shift or substitution based on the key.
	Output: The program returns the scrambled ciphertext.
	Reversal: The same (or a related) key is used to "undo" the math and recover the original message.
