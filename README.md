# Land Allocation

Case management for a land-allocation office: five-step cases, ID cards read with OCR (Sorani, Arabic, English), generated letters, reports and a full audit trail. It runs fully offline on the office's own computers.

> A public copy of a system built for an office, with the office's name, letterheads, templates and every piece of real data removed. Letters use plain placeholder templates: `python manage.py build_placeholder_templates`. How to run it: [`docs/running.md`](docs/running.md).

**Stack:** Django REST + Celery, PostgreSQL, Redis, React + Redux Toolkit (RTK Query), Tailwind, Tesseract OCR.
