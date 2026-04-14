# GreaterThan.sol
GreaterThan.sol
pragma solidity ^0.8.20;
contract GreaterThan {
    function check(uint a, uint b) public pure returns(bool) {
        return a > b;
    }
}
