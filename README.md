// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract MyToken {
    string public name = "MyToken";
    string public symbol = "BJR";
    uint256 public totalSupply = 10000000 * 10 ** 18; // Total supply of 10,000,000 tokens with 18 decimal places
    mapping(address => uint256) public balanceOf;

