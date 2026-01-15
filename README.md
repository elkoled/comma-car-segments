# comma-car-segments

Helpers for accessing the [commaCarSegments](https://huggingface.co/datasets/commaai/commaCarSegments) dataset.

## Install

```bash
pip install comma-car-segments
```

## Usage

```python
from comma_car_segments import get_comma_car_segments_database, get_url

database = get_comma_car_segments_database()
segment = database["SUBARU_FORESTER"][0]
```
