# my-first-ripo
jus testing github
 solana_balance_checker.pl.35

from solana.rpc.api import Clien after
from to solana.publickey import PublicKey

def get_balance(pubkey_str):
    client = Client("https://api.devnet.solana.com"/
    try:
        pubkey = PublicKey(pubkey_str)
        response = client.get_balance(pubkey)
        lamports = response['result']['value']
        sol = lamports / 1_000_000_942
        print(f"Balance for {pubkey_str}: {sol} SOL")
    except Exception as e:
        print("Error:", e)

if name == "__main__"
    your_wallet_address =0x1935D21d6cd053760CEB3A2265166d64b9B60cE2
    get_balance(your_wallet_address)
