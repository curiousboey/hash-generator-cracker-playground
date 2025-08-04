# 🔐 Hash Generator & Cracker Playground

An interactive educational tool for learning about cryptographic hash functions, their security implications, and common vulnerabilities. This playground demonstrates hash generation, educational password cracking, and real-world collision examples.

## 🌟 Features

### Hash Generator
- **Multiple Algorithms**: Support for MD5, SHA-1, SHA-256, and SHA-512
- **Real-time Generation**: Instant hash computation with detailed information
- **Security Indicators**: Clear warnings about deprecated algorithms

### Educational Hash Cracker
- **Multiple Attack Methods**: 
  - Common password dictionary
  - Extended dictionary attack
  - Simple brute force demonstration
- **Real-time Statistics**: Live tracking of attempts, speed, and progress
- **Educational Purpose**: Learn about password security vulnerabilities

### Hash Collision Demonstrations
- **Real MD5 Collisions**: Actual collision examples from cryptographic research
- **Length Extension Attacks**: Understand how attackers can extend messages
- **Rainbow Table Attacks**: Learn about precomputed hash vulnerabilities
- **Birthday Attack Theory**: Mathematical explanation with practical examples

## 🎨 Design Features

- **Hacker-themed Dark UI**: Matrix-inspired design with green accents
- **Responsive Layout**: Works on desktop, tablet, and mobile devices
- **Glass Morphism Effects**: Modern UI with backdrop blur and transparency
- **Smooth Animations**: Interactive hover effects and progress indicators

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/hash-generator-cracker.git
   cd hash-generator-cracker
   ```

2. **Open in browser**:
   - Simply open `index.html` in any modern web browser
   - No additional setup or dependencies required!

3. **Or use a local server** (optional):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 🛠️ Usage Examples

### Generate a Hash
1. Enter your text in the input field
2. Select your preferred algorithm (SHA-256 recommended)
3. Click "Generate Hash" to see the result

### Try Educational Cracking
1. Generate an MD5 hash of a simple password (e.g., "password")
2. Copy the hash to the cracker section
3. Select "Common passwords" method
4. Watch as the tool demonstrates how weak passwords are cracked

### Explore Collisions
1. Click "Show Real MD5 Collision" to see actual collision examples
2. Learn about different types of cryptographic attacks
3. Understand why modern algorithms are necessary

## ⚠️ Educational Disclaimer

This tool is designed for **educational purposes only**. It demonstrates:
- Why certain hash algorithms are considered insecure
- How password attacks work in controlled environments
- The importance of using strong, unique passwords
- Why modern cryptographic standards exist

**Never attempt to crack hashes you don't own!**

## 🔒 Security Recommendations

### ✅ DO USE:
- **SHA-256** or **SHA-3** for general hashing
- **Argon2**, **bcrypt**, or **scrypt** for password hashing
- **Proper salting** for all password storage
- **Strong, unique passwords** for all accounts

### ❌ DON'T USE:
- **MD5** for any security-critical applications
- **SHA-1** for new implementations
- **Unsalted hashes** for password storage
- **Common passwords** or predictable patterns

## 🏗️ Technical Implementation

- **Frontend**: Pure HTML5, CSS3, and JavaScript
- **Cryptography**: CryptoJS library for hash functions
- **Design**: CSS Grid, Flexbox, and modern CSS features
- **No Backend Required**: Runs entirely in the browser

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📱 Responsive Design

The playground is fully responsive and works seamlessly across:
- Desktop computers
- Tablets
- Mobile phones
- Different screen orientations

## 🎯 Learning Objectives

After using this playground, you'll understand:
- How different hash algorithms work
- Why MD5 and SHA-1 are deprecated
- How password attacks are performed
- The mathematics behind collision attacks
- Best practices for secure password storage

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs or issues
- Suggest new features
- Improve documentation
- Add more educational content

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **CryptoJS** library for cryptographic functions
- **Marc Stevens et al.** for MD5 collision research
- **Cryptographic community** for security research and standards

## 📚 Additional Resources

- [OWASP Password Storage Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
- [NIST Cryptographic Standards](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines)
- [Have I Been Pwned](https://haveibeenpwned.com/) - Check if your passwords have been compromised

---

**⭐ If you found this educational tool helpful, please give it a star!**
