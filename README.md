# Jungle-Zooo
A blockchain based dog adoption site.

### Setting up the development environment

There are a few technical requirements before we start. Please install the following:
 Node.js v6+ LTS and npm (comes with Node)
 Git
 
 ### Environment
 
 Truffle v5.3.4 (core: 5.3.4)
 Solidity v0.5.16 (solc-js)
 Node v13.13.0
 Web3.js v1.3.5
 npm 6.14.4
 MetaMask
 Ganache
 Solidity
 
 ### To RUN
 
 #### 1 Clone this repository in your system 
 
     git clone https://github.com/Surbhi-sys/Jungle-Zooo.git
 
 ### 2. Run the development console.
 
        truffle develop
        
   
       
 ### 3. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

       compile
       migrate
 
### 4. Open another ternminal and Run the liteserver development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.

// Serves the front-end on http://localhost:3000

     npm run dev
 
