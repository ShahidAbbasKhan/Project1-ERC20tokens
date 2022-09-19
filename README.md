# ERC20Mintable
 ## TokenName-My Silver Token
 ## Contract-Address:0xE3843612dCbF49feE7e048C1DDF655e7b618e40f
 ## Using Ropstem Test Net

- tokenName Function:

      will return token Name:
- tokenSymbol Function:

      will return token Symbol:
- tokenDecimal Function:

      will return that token has how many decimals.
- tokenSupply Function:

      will return  tokenSupply that token has.
- balanceOf Function:

      will return number of tokens of Specific  address.
- allowance Function:

      will return no. of tokens that are allowed (to execute) to specific
      address by the owner through Approve Function.
- mintTokens Function:

      only Owner of the Contract can call this function to Mint more Tokens then token
      supply also will be increased and owner Token balance will be increased as amount
      of the token as minted.
- burnTokens Function:

      only Owner of the Contract can call this function to burn Tokens then token supply
      also will be decreased and owner Token balance will be decreased as amount of the
      token is burned.
- transfer Function:

      Through this function a address having sufficent tokens can send tokens
      to other address besides zero address.
- approve Function:

      Through this function a address having sufficent tokens can Approve tokens
      for Spender address that address can transfer tokens to other addresses through
      transferFrom function. Spender address should not be Zero address.
- transferFrom Function:

      Through this function a Spender address having sufficent tokens that are approved 
      by Owner address to Spender address, Spender can transfer allowed tokens to
      other addresses within limit provided to Spender. Receiver address 
      should not be Zero address.

    
