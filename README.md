# base5b
Monitoring ETH Inflow to One Address
inflow = sum(tx["value"] for tx in block.transactions if tx["to"] == target)
print("Inflow:", inflow)
