# R6-tradeMerchant


حط هاذا الكود في ملف

\interact\shared\settings

    CreateThread(function()
    exports.interact:AddInteraction({
        coords = vector3(567.57, -1924.75, 24.75),
        distance = 4, -- optional
        interactDst = 2, -- optional
        options = {
            {
                type = "client",
                event = "openTrade",
                label = "Trade Merchant",
                params = {},
            },
        }
    })
end),
