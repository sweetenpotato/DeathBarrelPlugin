# DeathBarrelPlugin
## Outline (개요)
This plugin makes all of your items put in the barrel that is placed where you last died instead of dropping it to ground.

이 플러그인은 당신이 사망하였을 때 소지하고 있는 모든 아이템을 땅에 떨어뜨리는 대신 해당 위치에 통이 생성되고, 그 통에 당신의 소지품이 담기도록 합니다.

If y-coordinate of location of your death is lower than the minimum build height limit of the world, then the barrel will spawn 1 y-coordinate above.

만약에 사망한 지점의 y 좌표가 세계의 최소 건설 제한 높이보다 낮을 경우, 통은 그것보다 1 포인트 높은 곳에 생성됩니다.

Other cases are also the same.

다른 경우 또한 마찬가지 입니다.

## permissions

- deathbarrel.loot 
  - If you have this permission, it allows you to place the **deathbarrel** when you died.
  - 이 권한을 가지고 있다면, 죽을때 아이템을 드랍하는 대신 아이템이 모두 담긴 통을 생성합니다.

- deathbarrel.getmessage
  - If you have this permission, it allows you to get message about location of your death-barrel location.
  - 만약에 당신이 이 권한을 가지고 있다면, 죽을 때 생성되는 통의 정보가 담긴 메시지를 당신에게 전송합니다.

## minecraft version

- paper 1.18.x