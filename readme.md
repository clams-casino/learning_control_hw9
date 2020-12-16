# Model based exercise for AMoD class 2020


## Get started

In order to run without any problems the simulator you need to edit the `__init__.py` file in `notebooks/simulator/src/gym_duckietown/envs` as follow:

```Python
# coding=utf-8
# noinspection PyUnresolvedReferences
from ..wrappers import DiscreteWrapper
from ..envs.duckietown_env import DuckietownEnv
from ..envs.duckiebot_env import DuckiebotEnv
from ..envs.multimap_env import MultiMapEnv
```

The original file looks like :

```Python
# coding=utf-8
# noinspection PyUnresolvedReferences
from gym_duckietown.wrappers import DiscreteWrapper
from gym_duckietown.envs.duckietown_env import DuckietownEnv
from gym_duckietown.envs.duckiebot_env import DuckiebotEnv
from gym_duckietown.envs.multimap_env import MultiMapEnv
```

