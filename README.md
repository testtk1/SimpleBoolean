# SimpleBoolean
Deploy a contract on Base SimpleBoolean
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleBoolean {
    bool public value;

    function toggle() public {
        value = !value;
    }
}
