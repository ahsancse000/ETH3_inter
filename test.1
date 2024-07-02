// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract Token is ERC20, Ownable {
    constructor(address initialOwner)
        ERC20("chennai super", "kings")
        Ownable(initialOwner)
    {}

    // Burns tokens from the caller's balance
    function burn(uint256 amount) external {
        _burn(_msgSender(), amount);
    }

    // Mints new tokens and assigns them to the specified address
    function mint(address to, uint256 amount) external onlyOwner {
        _mint(to, amount);
    }

    // Overrides ERC20 transfer function to add custom logic if needed
    function transfer(address recipient, uint256 amount)
        public
        override
        returns (bool)
    {
        _transfer(_msgSender(), recipient, amount);
        return true;
    }
}
