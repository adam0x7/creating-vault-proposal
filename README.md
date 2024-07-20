# Creating a Proposal for Bera DAO on Tally

## Understanding Proof of Liquidity (PoL) and RewardsVaults

Proof of Liquidity (PoL) is fundamentally a governance-driven protocol, empowering the community to shape key aspects of the Berachain ecosystem. 

- Creating new RewardsVaults
- Establishing pools on BEX 
- and more

RewardsVaults (formerly known as Gauges) are smart contracts where users can stake their PoL-eligible assets to earn BGT rewards. These vaults are central to the PoL mechanism, serving as the primary means for users to participate in the ecosystem and earn rewards. RewardsVaults not only distribute BGT but also allow protocols to add incentives, allowing for protocols to bootstrap their own liquidity

## Steps to Create a Proposal on Tally for Bera DAO (bArtio testnet)

1. **Navigate to Tally**
   - Visit https://www.tally.xyz
   - Search for "Bera DAO"
   - Select the Bera DAO on the bArtic testnet

2. **Initiate New Proposal**
   - Click on the "Proposals" tab
   - Select "New Proposal" in the top right corner

3. **Draft Proposal Content**
   - Answer the following questions in your proposal:
     * What does your protocol do?
     * Why would users and validators want to be incentivized by your token in exchange for BGT?

4. **Set Up Custom Action**
   - In the "Actions" section, click "Add Custom Action"
   - Enter the BerachainRewardsVaultFactory address: `0x2B6e40f65D82A0cB98795bC7587a71bfa49fBB2B`

5. **Upload ABI and Select Function**
   - Click "Upload ABI"
   - Use this ABI: [BerachainRewardsVault.json](https://github.com/berachain/doc-abis/blob/main/core/BerachainRewardsVault.json)
   - Select "createRewardsVault" from the function dropdown

6. **Input Incentive Token**
   - Enter your incentive token's address in the provided field

7. **Submit Proposal**
   - Review all information
   - Click "Create Proposal"

8. **Confirm Transaction**
   - Ensure your wallet is connected
   - Confirm the transaction to submit the proposal

9. **Monitor Proposal**
   - Track your proposal's status on the Bera DAO Tally page
