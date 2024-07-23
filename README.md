# Daml Trading Market App

## Overview

Overview
This project was created by using the empty-skeleton template. The project adopts and exemplifies the proposal-accept design pattern. It was designed for a Trading Market App scenario.
The trader can create a TradeProposal contracts and "Cancel" & admin can exercise "ViewTrades", "Reject" or "Verify". The owner of the Tradeable can accept the trade.

## Workflow
- Trader1 creates TradeProposal contracts
- Admin exercises Reject with a note: "The Trade Proposal #3 is Not Fully Credible"
- Trader1 exercises Cancel with a note: "Trade Proposal #2 Cancelled by Requester" 
- Admin exercises Verify with admin note: "Trade Proposal #1 has been verified"
- Trader2 exercises AcceptTrade - a Trade contract is created
- Admin exercises ViewTrades - All Trades available are displayed
- Admin can Reject all TradeProposals that are older than 10 days

## Challenge(s)
SDK version is 2.8.5 and the code itself does not cause any issues/errors
The project was created by using empty-skeleton

## Compiling & Testing
To compile and test, run the pre-written script in the Test.daml under /daml OR run:
```
$ daml start
```