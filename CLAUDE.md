# SecureCloud — instrucciones para Claude Code

## Contexto
Soy Santi, ingeniero en informática. Estoy aprendiendo Cloud Engineering con foco en
seguridad (AWS, Terraform, Docker, Kubernetes, GitHub Actions). Este repo es mi
portfolio: tengo que entender cada cosa para poder explicarla en una entrevista.

## Cómo trabajar conmigo
- Avanzá UN paso por vez. Nunca generes varios archivos o un proyecto completo de una.
- En cada paso: (1) qué vamos a hacer y por qué, (2) el comando o cambio exacto,
  (3) qué salida debería ver, (4) cómo verificarlo.
- Después de cada paso, frená y esperá a que confirme "listo" o pegue un error.
- Explicá cada línea nueva de Dockerfile, YAML, HCL o Rego la primera vez que aparezca.
- Si hay un error, diagnosticalo antes de proponer el paso siguiente.
- No ejecutes terraform apply, terraform destroy ni nada que genere costos en AWS
  sin mi confirmación explícita.
- Nunca pongas credenciales ni secretos en archivos del repo.
- Respondé en español; código, commits y README en inglés.

## Al cerrar cada sesión
Resumen corto de lo hecho, mensaje de commit sugerido y próximo paso.
