# Artefacts Heal Limbs for Body Health System 

Artefacts that include health restoration in their tooltip + certain healing Perk Artefacts now slowly regen damaged limbs. This mod was made for S.T.A.L.K.E.R. GAMMA, but should work with non-GAMMA installs of Anomaly (balance may not make sense if player has a different artefact balance/stat setup).

Here is the healing formula:

 `Time to Heal All Limbs (+1 Limb HP) = [ (75 seconds) / (total healing level of all artefacts equipped) ]`

Here is the current table of the healing Artefacts (**at 100% Condition**):
- Oasis Heart = 1.5
- Kolobok = 1.5
- Firefly = 3
- Soul = 1
- Anomalous Sample "Mushroom" = 1
- Signet (when near campfire) = 0.8
- Sun (when outside and clear weather) = 0.58
- Chain (when in Sin faction) = 1
- Chain (when not in Sin faction) = 0.25
- Heart (when health is below threshold) = 0.8
- Lucifer = 1 (in backpack) or 3 (on belt)
- Bloodsucker Hide = 1

Artefacts' healing values are reduced when under 100% condition. So you can't get a 10% artefact and expect the full healing potential.

**Install this at the end of your load order.** If any mod other than "GAMMA Attachments Overhaul" replaces `zzz_player_injuries.script` from Body Health System/G.A.M.M.A. Medications Balance, this mod will conflict with it.

Credit goes to the "Campfire Heals Limbs" mod and "BHS Revolution" from ModDB for originally having an artefact limb healing system.
