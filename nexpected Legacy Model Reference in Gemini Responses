# Unexpected Legacy Model Reference in Gemini Responses

## Summary

During normal use of the Gemini Web UI, a response was observed that referenced a legacy Gemini 1.5-series model despite a newer model generation being selected in the user interface.

This report documents the observed behavior, user impact, and areas that may warrant investigation. It does not attempt to determine internal implementation details.

## Environment

- Service: Gemini Web UI
- Region: Japan
- Observation Type: User-side observation
- Observation Date: 2026

## Observed Behavior

While interacting with a currently available Gemini model, the response output contained references to "Gemini 1.5 Flash."

The reference appeared inconsistent with the model selected in the user interface at the time of observation.

## Expected Behavior

Users should receive responses consistent with the selected model configuration and should not encounter ambiguous references that suggest a different active model.

## User Impact

- Uncertainty regarding which model generated the response
- Difficulty evaluating model quality over time
- Reduced confidence in model-selection controls
- Increased difficulty when reporting issues or providing feedback

## Notes

This report records only the observed output behavior.

No assumptions are made regarding routing logic, fallback mechanisms, deployment strategy, or internal architecture.

## Conclusion

Model identification is an important part of trust and reproducibility when evaluating AI systems.
