# SelfDestruct.sol
pragma solidity ^0.8.20;
contract SelfDestruct {
    function destroy(address payable to) public {
        selfdestruct(to);
    }
}
