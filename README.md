
function createStartup{


creates startup with number of shares

.0001 ether is one share
}

function issueShares(ownerAddress, shareType, amount){
	shareType can be preferred or common (common shares allow user to vote)
	sendShar
}

function addOwner(ownerAddress){
	Add owner to ownershipArray
	//user is not
}

function removeSharesFromOwner(ownerAddress, numberSharesToRemove, typeOfShares){
	
	//takes owner address to be removed (only for common shares)
	// needs majority of common shares to remove the user, so keeps an array with owner to remove and number of shares to remove them

	if number of shares is greater than majority, common shares are revoked for user
}

function createOwnerAddress(nameOfOwner){
	
	creates contract address with the contract code to forward all amount to the company treasureChess once a transaction goes through address
}

function createVestingAgrrement(numberOfShare, typeof owner, epoch time of maturity, vestingPeriod, vestingMilestones[], endingBonusAmount){

//Simply saves the rules of a users shares

//users later votes with common shares to issue shares to a user

//vesting period is weekly, bimonthy, monthly, daily, quarterly, biannaully, or annually and amount to issue each week/month/etc.

epoch times are generated for each date of issuance between now and epoch time

endingBonusAmount is amount extra to reward at end of vesting period

vestingMilestones is array of milestone title and amount of shares/type of shares to isse for that milestone




this information is returned in whoNeedsIssuance
	
}

function whoNeedsIssuance(){
	
	returns people(addresses) of people who need to be issued shares 

}

function createCompanySavings(){
	All contract money goes here once they are sent to owners Contracts
	this is called when contract is created
	returns address of contract and private key


}

function changeCompanySavings(){
	
}

function createESOP(){
	//created when company is created and all share that don't go to people are stored here, and issued from here, and go back here when stock is removed from another user
	//This is contract that needs address	

}


function getCurrentShares(){
	
	returns array of owners, their names (if address has name), and number of common/ preferred shares they own


}

function getPendingShares(){
	
	returns array of owners, their names, how how many shares thay have vesting both preferred and common
}

function createNewShares(amount, type){
	
	//requires vote of all majority of common shares (owners there of) to issue prefferred or common shares.
	They go into ESOP (Employee Stock Option Program account)

}

function  terminateCompany(){
	
	//needs majority of votes. Preferred share holders get all ether back from companySavings, then common share holders

}

function nameCompany(){
	names the company, can be changed later, saves date ths occured
}

function saveArticles(text){
//optional
	saves articles of company (contract as data)
}

setNewShareValue(){
	
	changes value of shares from .0001 needed to issue per shares
	need majority common shares to issue
}





